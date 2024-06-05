<h1>Blog API REST</h1>

<p>Ce repository contient le code source d'un blog que j'ai utilisé pour m'entraîner avec les API REST. Vous pouvez cloner ce repository et lancer l'application localement en suivant les instructions ci-dessous.</p>

<h2>Prérequis</h2>

<ul>
    <li><a href="https://nodejs.org/" target="_blank">Node.js</a> doit être installé sur votre machine.</li>
</ul>

<h2>Installation</h2>

<ol>
    <li><strong>Cloner le repository :</strong></li>
</ol>

<pre><code>git clone https://github.com/Ikerpaipai/Blog.git</code></pre>

<ol start="2">
    <li><strong>Se déplacer dans le répertoire du projet :</strong></li>
</ol>

<pre><code>cd Blog</code></pre>

<ol start="3">
    <li><strong>Installer les dépendances :</strong></li>
</ol>

<pre><code>npm install</code></pre>

<h2>Lancer l'application</h2>

<ol>
    <li><strong>Lancer le serveur API :</strong></li>
</ol>

<pre><code>node server.js</code></pre>

<p>Le serveur API sera lancé sur <code>http://localhost:4000</code>.</p>

<ol start="2">
    <li><strong>Lancer l'application web :</strong></li>
</ol>

<p>Dans un autre terminal, exécutez :</p>

<pre><code>node index.js</code></pre>

<p>L'application web sera lancée sur <code>http://localhost:3000</code>.</p>

<h2>Utilisation</h2>

<p>Vous pouvez maintenant accéder à l'application web en ouvrant votre navigateur et en allant sur <code>http://localhost:3000</code>.</p>

<h2>Fonctionnalités</h2>

<ul>
    <li>Création, lecture, mise à jour et suppression d'articles de blog via l'API REST.</li>
    <li>Interface utilisateur pour interagir avec le blog.</li>
</ul>
