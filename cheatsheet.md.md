<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>cheatsheet.md</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__left">
    <div class="stackedit__toc">
      
<ul>
<li><a href="#markup-hints">MARKUP HINTS</a></li>
<li><a href="#bash">BASH</a></li>
<li><a href="#git--github">GIT & GITHUB</a>
<ul>
<li></li>
<li><a href="#youve-created-a-new-branch-template-tutorial-without-committing-changes-on-your-existing-branch-implementazione-pagina">You’ve created a new branch (template-tutorial) without committing changes on your existing branch (implementazione-pagina)</a></li>
<li><a href="#delete-a-local-branch-and-also-delete-it-on-the-remote-repository-on-github">delete a local branch and also delete it on the remote repository on GitHub</a></li>
<li><a href="#i-want-to-synch-another-an-oldest-branch-named-template-tutorial-with-a-newest-branch-named-template-sheetlike-and-after-delete-this-last-one-template-sheetlike">I want to synch another an oldest branch named “template-tutorial” with a newest branch named template-sheetlike and after delete this last one (template-sheetlike)</a></li>
<li><a href="#automate-the-copy-of-a-file-from-a-repo-to-another-when-pushing-the-commit">Automate the copy of a file from a repo to another when pushing the commit</a></li>
<li><a href="#theory">Theory</a></li>
<li><a href="#real-case-if-i-have-another-branch-othe-then-main-in-repo2-i-can-do-it">Real Case: If I have another branch othe then main in repo2 I can do it:</a></li>
<li><a href="#git-cheatsheet">GIT CHEATSHEET</a></li>
<li><a href="#hooks">HOOKS</a></li>
</ul>
</li>
<li><a href="#wagtail">WAGTAIL</a>
<ul>
<li></li>
<li><a href="#content_panels-definition-in-the-blogpage-class">content_panels definition in the BlogPage class:</a></li>
<li><a href="#uso-dello-structbox-in-wagtail">Uso dello StructBox in Wagtail</a></li>
<li><a href="#caratteristiche-avanzate-di-diango---wagtail">Caratteristiche avanzate di Diango - Wagtail</a></li>
<li><a href="#wagtail-upgrade-process">WAGTAIL Upgrade process</a></li>
</ul>
</li>
<li><a href="#python">PYTHON</a>
<ul>
<li><a href="#spiegazione-attraverso-codice-di-init-getattribute-e-super">Spiegazione attraverso codice di init, getattribute e super</a></li>
<li><a href="#ed-ora-quando-posso-usare-e-non-usare-getattribute">Ed ora quando posso usare e non usare getattribute?</a></li>
<li><a href="#creating-an-instance-without-getattribute">Creating an instance without getattribute</a></li>
<li><a href="#mixin">MIXIN</a></li>
</ul>
</li>
<li><a href="#standard-commands-in-django-installation">STANDARD COMMANDS IN DJANGO INSTALLATION#</a></li>
<li><a href="#useful-property-and-method-in-django">USEFUL PROPERTY AND METHOD IN DJANGO</a>
<ul>
<li><a href="#luso-di-queryset">L’uso di Queryset</a></li>
</ul>
</li>
<li><a href="#git--github-1">GIT & GITHUB</a>
<ul>
<li></li>
<li><a href="#git-checkout--b-new-branch-name">- git checkout -b new-branch-name</a></li>
<li><a href="#il-comando-può-essere-visto-come-la-sintesi-dei-due-seguenti-comandi">Il comando può essere visto come la sintesi dei due seguenti comandi:</a></li>
<li><a href="#youve-created-a-new-branch-template-tutorial-without-committing-changes-on-your-existing-branch-implementazione-pagina-1">You’ve created a new branch (template-tutorial) without committing changes on your existing branch (implementazione-pagina)</a></li>
<li><a href="#delete-a-local-branch-and-also-delete-it-on-the-remote-repository-on-github-1">delete a local branch and also delete it on the remote repository on GitHub</a></li>
<li><a href="#i-want-to-synch-another-an-oldest-branch-named-template-tutorial-with-a-newest-branch-named-template-sheetlike-and-after-delete-this-last-one-template-sheetlike-1">I want to synch another an oldest branch named “template-tutorial” with a newest branch named template-sheetlike and after delete this last one (template-sheetlike)</a></li>
</ul>
</li>
<li><a href="#yaml-protocol">YAML PROTOCOL</a>
<ul>
<li></li>
</ul>
</li>
<li><a href="#wagtail-1">WAGTAIL</a>
<ul>
<li></li>
<li><a href="#uso-dello-structbox-in-wagtail-1">Uso dello StructBox in Wagtail</a></li>
</ul>
</li>
<li><a href="#caratteristiche-avanzate-di-diango---wagtail-1">Caratteristiche avanzate di Diango - Wagtail</a>
<ul>
<li><a href="#how-to-feed-a-table-from-django-admin-panel-open-in-as-block-into-wagtail-admin-panel-and-render-it-into-the-wagtail-frontend">HOW TO FEED A TABLE FROM DJANGO ADMIN PANEL, OPEN IN AS BLOCK INTO WAGTAIL ADMIN PANEL AND RENDER IT INTO THE WAGTAIL FRONTEND</a></li>
</ul>
</li>
<li><a href="#section">…</a>
<ul>
<li></li>
</ul>
</li>
<li><a href="#feeding-data-from-django-to-wagatail-via-api">FEEDING DATA FROM DJANGO TO WAGATAIL VIA API</a>
<ul>
<li></li>
<li><a href="#definitive-code-for-mini-django-project-api">Definitive Code for mini Django project API</a></li>
</ul>
</li>
<li><a href="#python-1">PYTHON</a>
<ul>
<li><a href="#spiegazione-attraverso-codice-di-init-getattribute-e-super-1">Spiegazione attraverso codice di init, getattribute e super</a></li>
<li><a href="#creating-an-instance-without-init-1">Creating an instance without init</a></li>
<li><a href="#this-will-not-raise-an-error-but-the-instance-wont-have-a-brand-attribute.-1">This will not raise an error, but the instance won’t have a ‘brand’ attribute.</a></li>
</ul>
</li>
<li><a href="#creating-an-instance-with-init-1">Creating an instance with init</a></li>
<li><a href="#now-the-brand-attribute-is-initialized-during-instantiation.">Now, the ‘brand’ attribute is initialized during instantiation.</a>
<ul>
<li>
<ul>
<li></li>
</ul>
</li>
<li><a href="#creating-an-instance-without-getattribute-1">Creating an instance without getattribute</a></li>
<li><a href="#accessing-the-brand-attribute-without-a-custom-getattribute-1">Accessing the ‘brand’ attribute without a custom getattribute</a></li>
<li><a href="#mixin-1">MIXIN</a></li>
</ul>
</li>
<li><a href="#standard-commands-in-django-installation-1">STANDARD COMMANDS IN DJANGO INSTALLATION#</a></li>
<li><a href="#useful-property-and-method-in-django-1">USEFUL PROPERTY AND METHOD IN DJANGO</a>
<ul>
<li><a href="#luso-di-queryset-1">L’uso di Queryset</a></li>
<li><a href="#strumenti-avanzati-creare-una-pagina-wagtail-allinterno-di-un-sito-django"># Strumenti avanzati: Creare una pagina wagtail all’interno di un sito Django</a></li>
<li><a href="#so-now-update-the-urls-and-run-makemirgations-and-migrate">So now update the urls and run makemirgations and migrate</a></li>
</ul>
</li>
<li><a href="#django">DJANGO</a>
<ul>
<li><a href="#create-a-django-app-from-0-from-create-django-api-app-">Create a Django App from 0 (from Create Django API App )</a></li>
<li><a href="#step-16-bis-problems-with-git-push">Step 16 bis: problems with git push</a></li>
</ul>
</li>
<li><a href="#advanced-bash-commands--django">ADVANCED BASH COMMANDS & DJANGO</a>
<ul>
<li><a href="#comando-per-generare-pagine-in-hugo">Comando per generare pagine in Hugo</a></li>
</ul>
</li>
</ul>

    </div>
  </div>
  <div class="stackedit__right">
    <div class="stackedit__html">
      <p>[toc]</p>
<h1 id="markup-hints">MARKUP HINTS</h1>
<p>By Mauro alle h.13:16<br>
I have my <a href="http://README.md">README.md</a> inside my project. Here are a method to work with your <a href="http://README.md">README.md</a> separately while working on your vsc local project: Use an external Markdown editor like</p>
<p>** (a minimal markdown editor and reader) **. These editors provide a live preview feature by default.</p>
<h1 id="bash">BASH</h1>
<ul>
<li>
<p>trovare la oporta occupata:</p>
<ul>
<li><code>lsof -i :8000</code></li>
</ul>
</li>
<li>
<p>chiudere la porta occupata forzatamente:</p>
<ul>
<li><code>kill -9 32394(esempio)</code></li>
</ul>
</li>
<li>
<p>vedere i comandi che iniziano per una determinata strina effettuati in precedenza:</p>
<ul>
<li><code>history | grep "kill (esempio)"</code></li>
</ul>
</li>
<li>
<p>trovare la porta occupata:</p>
<ul>
<li><code>lsof -i :8000</code></li>
</ul>
</li>
<li>
<p>chiudere la porta occupata forzatamente:</p>
<ul>
<li><code>kill -9 32394(esempio)</code></li>
</ul>
</li>
<li>
<p>vedere i comandi che iniziano per una determinata strina effettuati in precedenza:</p>
<ul>
<li><code>history | grep "kill (esempio)"</code></li>
</ul>
</li>
<li>
<p>Azione Bash - Quello che segue è uno script molto importante che permette nell’ordine di 1) verificare se la porta 8000 (che viene utilizzata normalmente in fase di sviluppo) è occupata ed eventualmente chiuderla; 2) aprire Django 3) aprire hugo. Al momento sono presenti due file separati per una migliore comprensione:</p>
</li>
</ul>
<pre class=" language-bash"><code class="prism  language-bash">- check_ports.sh

  \#<span class="token operator">!</span>/bin/bash

  \# Check <span class="token keyword">if</span> any process is listening on port 8000

  <span class="token keyword">if</span> <span class="token function">lsof</span> -i :8000 <span class="token operator">&gt;</span>/dev/null 2<span class="token operator">&gt;</span><span class="token operator">&amp;</span>1<span class="token punctuation">;</span> <span class="token keyword">then</span>

  ​    <span class="token keyword">echo</span> <span class="token string">"Port 8000 is in use."</span>

  ​    \# Get the PID of the process using port 8000

  ​    pid<span class="token operator">=</span><span class="token variable"><span class="token variable">$(</span><span class="token function">lsof</span> -ti :8000<span class="token variable">)</span></span>

  ​    \# Kill the process

  ​    <span class="token keyword">echo</span> <span class="token string">"Killing process with PID <span class="token variable">$pid</span>"</span>

  ​    <span class="token function">kill</span> -9 <span class="token string">"<span class="token variable">$pid</span>"</span>

  ​    <span class="token keyword">echo</span> <span class="token string">"Process killed."</span>

  <span class="token keyword">else</span>

  ​    <span class="token keyword">echo</span> <span class="token string">"Port 8000 is not in use."</span>

  <span class="token keyword">fi</span>
</code></pre>
<ul>
<li>
<pre class=" language-bash"><code class="prism  language-bash">run_project.sh
<span class="token comment">#!/bin/bash</span>

<span class="token comment"># Navigate to the Django project directory and run the server</span>
<span class="token comment"># cd /progetto_api</span>
python3 manage.py runserver <span class="token operator">&amp;</span>

<span class="token comment"># Navigate to the Hugo project directory and run the server</span>
<span class="token function">cd</span> ./sgb_start/
hugo server -D


</code></pre>
</li>
</ul>
<p>Per cui lo script generare <strong>APRIRE I DUE PROGRAMMI</strong>  DJANGO E HUGO è il seguente (ADA PERFEZIONARE!!):</p>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token shebang important">#!/bin/bash</span>

<span class="token comment"># Check if any process is listening on port 8000</span>
<span class="token keyword">if</span> <span class="token function">lsof</span> -i :8000 <span class="token operator">&gt;</span>/dev/null 2<span class="token operator">&gt;</span><span class="token operator">&amp;</span>1<span class="token punctuation">;</span> <span class="token keyword">then</span>
    <span class="token keyword">echo</span> <span class="token string">"Port 8000 is in use."</span>

    <span class="token comment"># Get the PID of the process using port 8000</span>
    pid<span class="token operator">=</span><span class="token variable"><span class="token variable">$(</span><span class="token function">lsof</span> -ti :8000<span class="token variable">)</span></span>

    <span class="token comment"># Kill the process</span>
    <span class="token keyword">echo</span> <span class="token string">"Killing process with PID <span class="token variable">$pid</span>"</span>
    <span class="token function">kill</span> -9 <span class="token string">"<span class="token variable">$pid</span>"</span>

    <span class="token keyword">echo</span> <span class="token string">"Process killed."</span>
<span class="token keyword">else</span>
    <span class="token keyword">echo</span> <span class="token string">"Port 8000 is not in use."</span>
<span class="token keyword">fi</span>


<span class="token comment"># Navigate to the Django project directory and run the server</span>
<span class="token comment"># cd /progetto_api</span>
python3 manage.py runserver <span class="token operator">&amp;</span>

<span class="token comment"># Navigate to the Hugo project directory and run the server</span>
<span class="token function">cd</span> ./sgb_start/
hugo server -D
</code></pre>
<p>Mentre il codice per chiudere i due programmi DJANGO e HUGO è il seguente (da perfezionare)!!!:</p>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token comment"># Find Django PID and send SIGTERM signal</span>
django_pid<span class="token operator">=</span><span class="token variable"><span class="token variable">$(</span>pidof python<span class="token variable">)</span></span> <span class="token operator">&amp;&amp;</span> <span class="token function">kill</span> <span class="token string">"<span class="token variable">$django_pid</span>"</span> <span class="token operator">&amp;&amp;</span> <span class="token keyword">echo</span> <span class="token string">"Django process terminated"</span>

<span class="token comment"># Find Hugo PID and send SIGTERM signal</span>
hugo_pid<span class="token operator">=</span><span class="token variable"><span class="token variable">$(</span>pidof hugo<span class="token variable">)</span></span> <span class="token operator">&amp;&amp;</span> <span class="token function">kill</span> <span class="token string">"<span class="token variable">$hugo_pid</span>"</span> <span class="token operator">&amp;&amp;</span> <span class="token keyword">echo</span> <span class="token string">"Hugo process terminated"</span>
<span class="token function">ps</span> aux <span class="token operator">|</span> <span class="token function">grep</span> <span class="token string">"python manage.py runserver"</span><span class="token punctuation">;</span> reset


</code></pre>
<h1 id="git--github">GIT &amp; GITHUB</h1>
<p>Riferimenti <a href="https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax">Mastering MarkDown</a></p>
<h3 id="ricordarsi-di-aggiungere-.gitgnore">Ricordarsi di aggiungere .gitgnore</h3>
<p><strong>- git add .gitignore</strong><br>
<strong>- git commit -m "Add .gitignore to exclude compiled Python files"</strong></p>
<h3 id="per-effettuare-il-push-da-origine-a-remoto">Per effettuare il push da origine a remoto</h3>
<p><strong>- git push origin implementazione-pagina</strong></p>
<h3 id="switch-to-the-new-branch">Switch to the New Branch:</h3>
<p><strong>- git checkout new-branch-name</strong></p>
<h3 id="creare-una-nuova-branch-e-posizionarsi-sulla-stessa">Creare una nuova branch e posizionarsi sulla stessa</h3>
<ul>
<li>git checkout -b new-branch-name <em>(Il comando può essere visto come la sintesi dei due seguenti comandi:)</em></li>
</ul>
<p><strong>- git branch new-branch-name  # Create a new branch</strong><br>
<strong>- git checkout new-branch-name  # Switch to the new branch</strong></p>
<h2 id="youve-created-a-new-branch-template-tutorial-without-committing-changes-on-your-existing-branch-implementazione-pagina">You’ve created a new branch (template-tutorial) without committing changes on your existing branch (implementazione-pagina)</h2>
<p>To address this, you’ll need to follow these steps to commit your changes on the implementazione-pagina branch and then switch back to the template-tutorial branch. Here’s a step-by-step guide:</p>
<ul>
<li>Commit Changes on implementazione-pagina:<br>
Assuming you are currently on the template-tutorial branch, ** switch back to the implementazione-pagina branch:**</li>
</ul>
<p><code>git checkout implementazione-pagina</code></p>
<p>Now, add and commit your changes:</p>
<p><code>git add .</code><br>
<code>git commit -m "Your commit message here"</code></p>
<ul>
<li><strong>Push Changes to Remote (implementazione-pagina):</strong><br>
Assuming the remote branch is named implementazione-pagina:</li>
</ul>
<p><code>git push origin implementazione-pagina</code></p>
<ul>
<li>** Switch Back to template-tutorial:**<br>
Now, switch back to the template-tutorial branch:</li>
</ul>
<p><code>git checkout template-tutorial</code></p>
<p><strong>If you haven’t pushed the template-tutorial branch yet, you can push it to the remote repository when you’re ready:</strong></p>
<p><code>git push origin template-tutorial</code></p>
<p><strong>How can see from my vsc local if a git branch is present also in the remote github?</strong></p>
<p><code>git fetch --all git branch -a</code><br>
This fetches all branches from the remote repository and lists both local and remote branches. Remote branches are prefixed with “remotes/origin/”. Check if your branch is listed among the remotes.</p>
<p><strong>Come posso creare una nuova branch in local, e poi crearla anche in Github, poi effettuare il push e rendere questa branch principale?</strong></p>
<p>Create a new branch locally and switch to it (chimiamo la nuova branch template-tutorial):<br>
<code>git checkout -b template-tutorial</code></p>
<p>Push the new branch to GitHub:</p>
<p><code>git push origin template-tutorial</code></p>
<p>Set the upstream for the new branch:</p>
<p><code>git branch --set-upstream-to=origin/template-tutorial template-tutorial</code>![alt]( ‘{“class”: “”, “title”: “”}’)</p>
<p>Now, further pushes can be simplified to:</p>
<p><code>git push</code></p>
<p>To revert the changes and go back to the original commit before the changes, you can use the following commands:<br>
<code>git reset --hard HEAD git clean -fd</code></p>
<p>The first command (git reset --hard HEAD) resets your branch to the latest commit, discarding changes. The second command (git clean -fd) removes untracked files and directories. Use them with caution, as they are not reversible.</p>
<p>-fd stands for what?<br>
In the context of the git clean command:</p>
<p>-f stands for force.<br>
-d stands for directory.<br>
Together, -fd means force removal of untracked directories. This option is used to remove untracked files and directories forcefully.</p>
<h2 id="delete-a-local-branch-and-also-delete-it-on-the-remote-repository-on-github">delete a local branch and also delete it on the remote repository on GitHub</h2>
<p>Delete the local branch:</p>
<p><code>git branch -d branch_name</code>![alt]( ‘{“class”: “”, “title”: “”}’)</p>
<p>Replace branch_name with the name of the branch you want to delete.</p>
<p>If the branch contains unmerged changes, you might need to force delete it:</p>
<p><code>git branch -D branch_name</code></p>
<p>Delete the remote branch:</p>
<p><code>git push origin --delete branch_name</code></p>
<p>This will delete the branch on the remote repository (GitHub).</p>
<p>Update your local repository to reflect the changes on the remote:</p>
<p><code>git fetch --prune</code></p>
<p>The --prune flag removes any remote tracking branches that no longer exist on the remote.</p>
<h2 id="i-want-to-synch-another-an-oldest-branch-named-template-tutorial-with-a-newest-branch-named-template-sheetlike-and-after-delete-this-last-one-template-sheetlike">I want to synch another an oldest branch named “template-tutorial” with a newest branch named template-sheetlike and after delete this last one (template-sheetlike)</h2>
<p>Switch to the template-tutorial branch:<br>
<code>git switch template-tutorial</code></p>
<p>Rebase template-sheetlike onto template-tutorial:<br>
<code>git rebase template-sheetlike</code></p>
<p>Push the changes to the remote repository:<br>
<code>git push origin template-tutorial --force</code><br>
Note: Force-pushing after a rebase rewrites the commit history. Use it with caution, especially if the branch has already been shared with others</p>
<p>Delete the template-sheetlike branch:<br>
<code>git branch -d template-sheetlike</code><br>
<code>git push origin --delete template-sheetlike</code></p>
<h2 id="automate-the-copy-of-a-file-from-a-repo-to-another-when-pushing-the-commit">Automate the copy of a file from a repo to another when pushing the commit</h2>
<p>So let’s say that i have <a href="http://cheatsheet.md">cheatsheet.md</a> that i update regularly as it would be a wiki page. This file with the same name is present on different local repo. Let’s say that i am working into my local repo named /home/mauro/Scrivania/dJANGO_apI/progetto_api/cheatsheet.md.md. When I do a commit adn after a push into github repo <a href="https://github.com/progettazionemauro/django-api">https://github.com/progettazionemauro/django-api</a> I want automatically copy this file and update the commit also into my <a href="https://github.com/progettazionemauro/wiki-wag">https://github.com/progettazionemauro/wiki-wag</a> How can do that automatically?</p>
<p>To automatically copy and update the <code>cheatsheet.md</code> file in another GitHub repository whenever you push changes to the first repository, you can use GitHub Actions. GitHub Actions allows you to define workflows that run in response to various events, such as pushing to a repository. Here’s a simple example:</p>
<h2 id="theory">Theory</h2>
<ol>
<li>
<h3 id="create-a-github-actions-workflow"><strong>Create a GitHub Actions Workflow:</strong></h3>
<p>In your Django API repository (<code>https://github.com/progettazionemauro/django-api</code>), create a directory named <code>.github/workflows</code> if it doesn’t already exist.</p>
<p>Inside this directory, create a file named, for example, <code>sync_cheatsheet.yml</code> with the following content:</p>
<pre><code>name: Sync Cheatsheet

on:
  push:
    branches:
      - main

jobs:
  sync:
    runs-on: ubuntu-latest

    steps:
    - name: Checkout repository
      uses: actions/checkout@v2

    - name: Copy cheatsheet to other repository
      run: |
        cp cheatsheet.md /path/to/wiki-wag-repo
        cd /path/to/wiki-wag-repo
        git config user.email "your-email@example.com"
        git config user.name "Your Name"
        git add cheatsheet.md
        git commit -m "Sync cheatsheet from django-api repository"
        git push origin main
</code></pre>
<p>Replace <code>/path/to/wiki-wag-repo</code> with the actual path to your local <code>wiki-wag</code> repository.</p>
</li>
<li>
<p><strong>Commit and Push Workflow:</strong></p>
<p>Commit the changes and push them to your Django API repository:</p>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token function">git</span> add .github/workflows/sync_cheatsheet.yml
<span class="token function">git</span> commit -m <span class="token string">"Add sync cheatsheet workflow"</span>
<span class="token function">git</span> push origin main
</code></pre>
</li>
<li>
<p><strong>Run the Workflow:</strong></p>
<p>The workflow will run automatically when you push changes to the <code>main</code> branch. It will copy the <code>cheatsheet.md</code> file to the specified path in the <code>wiki-wag</code> repository and commit the changes there.</p>
</li>
</ol>
<p>Make sure to replace the placeholder values in the workflow file (<code>your-email@example.com</code>, <code>Your Name</code>, and <code>/path/to/wiki-wag-repo</code>) with your actual email, name, and the path to the <code>wiki-wag</code> repository.</p>
<p>Here are step-by-step instructions to set up the GitHub Actions workflow for syncing the <code>cheatsheet.md</code> file from the Django API repository to the <code>wiki-wag</code> repository:</p>
<h4 id="step-1-create-the-workflow-file">Step 1: Create the Workflow File</h4>
<ol>
<li>
<p>Open your Django API repository in your code editor or on GitHub.</p>
</li>
<li>
<p>Inside the <code>.github/workflows</code> directory (create it if it doesn’t exist), create a new file named, for example, <code>sync_cheatsheet.yml</code>.</p>
</li>
<li>
<p>Copy and paste the following content into <code>sync_cheatsheet.yml</code>:</p>
<pre><code>yamlCopy codename: Sync Cheatsheet

on:
  push:
    branches:
      - main

jobs:
  sync:
    runs-on: ubuntu-latest

    steps:
    - name: Checkout repository
      uses: actions/checkout@v2

    - name: Copy cheatsheet to other repository
      run: |
        cp cheatsheet.md /path/to/wiki-wag-repo
        cd /path/to/wiki-wag-repo
        git config user.email "your-email@example.com"
        git config user.name "Your Name"
        git add cheatsheet.md
        git commit -m "Sync cheatsheet from django-api repository"
        git push origin main
</code></pre>
<p>Replace <code>/path/to/wiki-wag-repo</code>, <code>"your-email@example.com"</code>, and <code>"Your Name"</code> with the actual path to your local <code>wiki-wag</code> repository, your email, and your GitHub username.</p>
</li>
</ol>
<h4 id="step-2-commit-and-push-workflow-file">Step 2: Commit and Push Workflow File</h4>
<ol>
<li>
<p>In your terminal, navigate to the Django API repository.</p>
</li>
<li>
<p>Run the following commands to stage, commit, and push the workflow file:</p>
<pre><code>bashCopy codegit add .github/workflows/sync_cheatsheet.yml
git commit -m "Add sync cheatsheet workflow"
git push origin main
</code></pre>
</li>
</ol>
<h4 id="step-3-run-the-workflow">Step 3: Run the Workflow</h4>
<ol>
<li>Visit the Actions tab on your GitHub repository to see the status of your workflow. You should see the “Sync Cheatsheet” workflow running or completed.</li>
</ol>
<h4 id="step-4-verify-changes-in-the-wiki-wag-repository">Step 4: Verify Changes in the <code>wiki-wag</code> Repository</h4>
<ol>
<li>
<p>After the workflow completes, check your <code>wiki-wag</code> repository for the synced changes to the <code>cheatsheet.md</code> file.</p>
<p>If there are any issues or changes are not reflected as expected, review the GitHub Actions logs for the workflow to identify potential errors.</p>
</li>
</ol>
<p>That’s it! You’ve set up a GitHub Actions workflow to automatically sync the <code>cheatsheet.md</code> file from the Django API repository to the <code>wiki-wag</code> repository on each push to the <code>main</code> branch.</p>
<h5 id="break-down-the-content-of-the-github-actions-workflow-file-step-by-step">Break down the content of the GitHub Actions workflow file step by step:</h5>
<pre class=" language-yaml"><code class="prism  language-yaml"><span class="token key atrule">name</span><span class="token punctuation">:</span> Sync Cheatsheet
</code></pre>
<ul>
<li>This line sets the name of the GitHub Actions workflow to “Sync Cheatsheet.”</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml">  <span class="token key atrule">push</span><span class="token punctuation">:</span>
    <span class="token key atrule">branches</span><span class="token punctuation">:</span>
      <span class="token punctuation">-</span> main
</code></pre>
<ul>
<li>This section specifies the trigger for the workflow. The workflow will be triggered on each push to the <code>main</code> branch.</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml">  <span class="token key atrule">sync</span><span class="token punctuation">:</span>
    <span class="token key atrule">runs-on</span><span class="token punctuation">:</span> ubuntu<span class="token punctuation">-</span>latest
</code></pre>
<ul>
<li>Here, we define a job named “sync” that will run on the latest version of the Ubuntu operating system.</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml"><span class="token key atrule">steps</span><span class="token punctuation">:</span>
    <span class="token punctuation">-</span> <span class="token key atrule">name</span><span class="token punctuation">:</span> Checkout repository
      <span class="token key atrule">uses</span><span class="token punctuation">:</span> actions/checkout@v2
</code></pre>
<ul>
<li>This step checks out the code from the repository, allowing subsequent steps to operate on the repository’s contents.</li>
<li><code>uses: actions/checkout@v2</code>: This part specifies the action that will be used for this step. In GitHub Actions, an action is a reusable unit of code. The <code>actions/checkout</code> action is provided by GitHub and is commonly used to check out the source code of the repository.
<ul>
<li><code>@v2</code>: This refers to the version of the <code>actions/checkout</code> action to use. In this case, it’s version 2 of the action. The <code>@v2</code> is a version tag that indicates a specific release or version of the action. Using a version tag ensures that the workflow is using a stable and known version of the action, making it less prone to unexpected changes.</li>
</ul>
</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml"><span class="token punctuation">-</span> <span class="token key atrule">name</span><span class="token punctuation">:</span> Copy cheatsheet to other repository
      <span class="token key atrule">run</span><span class="token punctuation">:</span> <span class="token punctuation">|</span><span class="token scalar string">
        cp cheatsheet.md /path/to/wiki-wag-repo
        cd /path/to/wiki-wag-repo</span>
</code></pre>
<ul>
<li>In this step, the <code>cheatsheet.md</code> file is copied from the current repository to the specified path (<code>/path/to/wiki-wag-repo</code>). The subsequent commands are executed within the <code>wiki-wag</code> repository.</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml">git config user.email "your<span class="token punctuation">-</span>email@example.com"
        git config user.name "Your Name"
</code></pre>
<ul>
<li>These commands set the global Git configuration for the user’s email and name in the <code>wiki-wag</code> repository.</li>
</ul>
<pre class=" language-bash"><code class="prism  language-bash">        <span class="token function">git</span> add cheatsheet.md
</code></pre>
<ul>
<li>This command stages the changes to the <code>cheatsheet.md</code> file for the next commit.</li>
</ul>
<pre class=" language-bash"><code class="prism  language-bash">        <span class="token function">git</span> commit -m <span class="token string">"Sync cheatsheet from django-api repository"</span>
</code></pre>
<ul>
<li>This command creates a new commit with a commit message indicating that the <code>cheatsheet.md</code> file is being synced from the <code>django-api</code> repository.</li>
</ul>
<pre class=" language-bash"><code class="prism  language-bash">        <span class="token function">git</span> push origin main
</code></pre>
<ul>
<li>
<p>Finally, this command pushes the changes to the remote repository (<code>origin</code>) on the <code>main</code> branch.</p>
<h2 id="real-case-if-i-have-another-branch-othe-then-main-in-repo2-i-can-do-it">Real Case: If I have another branch othe then main in repo2 I can do it:</h2>
<pre class=" language-yaml"><code class="prism  language-yaml"><span class="token key atrule">name</span><span class="token punctuation">:</span> Sync Cheatsheet 
<span class="token key atrule">on</span><span class="token punctuation">:</span>  
	<span class="token key atrule">push</span><span class="token punctuation">:</span>    
		<span class="token key atrule">branches</span><span class="token punctuation">:</span>      
			<span class="token punctuation">-</span> main 
<span class="token key atrule">jobs</span><span class="token punctuation">:</span>  
	<span class="token key atrule">sync</span><span class="token punctuation">:</span>    
		<span class="token key atrule">runs-on</span><span class="token punctuation">:</span> ubuntu<span class="token punctuation">-</span>latest     
		<span class="token key atrule">steps</span><span class="token punctuation">:</span>    
		<span class="token punctuation">-</span> <span class="token key atrule">name</span><span class="token punctuation">:</span> Checkout repository      
		<span class="token key atrule">uses</span><span class="token punctuation">:</span> actions/checkout@v2      
		<span class="token key atrule">with</span><span class="token punctuation">:</span>        
		<span class="token key atrule">ref</span><span class="token punctuation">:</span> opzione<span class="token punctuation">-</span>pagina  <span class="token comment"># Specify the branch you want to sync</span>
</code></pre>
</li>
</ul>
<h3 id="summary">Summary</h3>
<p>The GitHub Actions workflow automates the process of syncing the <code>cheatsheet.md</code> file from the <code>django-api</code> repository to the <code>wiki-wag</code> repository. It does so by copying the file, committing the changes, and pushing the commit to the <code>main</code> branch of the <code>wiki-wag</code> repository whenever changes are pushed to the <code>main</code> branch of the <code>django-api</code> repository.</p>
<h3 id="some-useful-notes">Some useful notes</h3>
<p>Merge:<br>
Creates Merge Commits: When you merge one branch into another, Git creates a new merge commit that has two parent commits: <strong>one from the branch you’re merging and another from the branch you’re merging into.<br>
This results in a non-linear history with multiple branches merging into each other</strong><br>
Preserves Original History:</p>
<p>The original commits from both branches remain unchanged. This approach keeps a clear record of when changes were made on each branch.</p>
<p>Rebase:<br>
Linearizes History:</p>
<p>Rebase is used to linearize the commit history. It moves or combines a sequence of commits to a new base commit.<br>
When you rebase one branch onto another, it effectively transplants the entire branch onto the tip of the other branch, creating a linear history.<br>
No Merge Commits:</p>
<p>Unlike merge, rebase doesn’t create additional merge commits.<br>
It can result in a cleaner, more linear history.<br>
When to Choose Each Approach:<br>
Merge:</p>
<p>Use merge when you want to preserve the original commit history, especially when collaborating with others.<br>
Good for feature branches and when you want to maintain a clear record of branch integration points.<br>
Rebase:</p>
<p>Use rebase when you want a clean, linear history and don’t mind rewriting commits.<br>
Useful for feature branches before merging into a shared branch to avoid unnecessary merge commits.<br>
Switch vs. Checkout:<br>
git switch is a more modern and user-friendly command introduced in recent versions of Git. It is designed specifically for branch switching. If you’re using a version of Git that supports git switch, you can replace git checkout with git switch:</p>
<p>Switching Branch:<br>
git switch template-tutorial<br>
Both commands essentially do the same thing in this context, but git switch provides a clearer and more explicit syntax for branch-related operations. If your Git version supports it, feel free to use git switch instead of git checkout.</p>
<h2 id="git-cheatsheet">GIT CHEATSHEET</h2>
<p>git command to see the last 3 commit with oneline :</p>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token function">git</span> log --oneline -n 3
</code></pre>
<h2 id="hooks">HOOKS</h2>
<h3 id="hook-per-sincronizzare-un-file-di-testo-da-stckbit-con-lintera-directory-proveniente-dal-local.-questo-script-è-molto-potente-in-quanto-selettivamente-recupera-dal-remote-il-file-di-interesse-lo-sovrascrive-forzatamente-nella-locale-e-poi-qualsiasi-cambio-in-local-sul-file-non-viene-considerato">Hook per sincronizzare un file di testo da stckbit con l’intera directory proveniente dal local. Questo script è molto potente in quanto selettivamente recupera dal remote il file di interesse lo sovrascrive forzatamente nella locale e poi qualsiasi cambio in local sul file non viene considerato</h3>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token comment">## Mauro 1/5/24 - h. 13:11</span>

<span class="token comment">#!/bin/bash</span>



<span class="token comment"># Fetch latest changes from the remote repository</span>

<span class="token function">git</span> fetch origin



<span class="token comment"># Pull the latest version of cheatsheet.md from the remote and overwrite local changes</span>

<span class="token function">git</span> pull origin main --force



<span class="token comment"># Remove any local changes to cheatsheet.md</span>

<span class="token function">git</span> checkout -- cheatsheet.md



<span class="token comment"># Continue with the rest of the script</span>

<span class="token comment"># Add all changes to the staging area</span>

<span class="token function">git</span> add <span class="token keyword">.</span>



<span class="token comment"># Commit all staged changes</span>

<span class="token function">git</span> commit -m <span class="token string">"Auto-commit before pushing changes"</span>



<span class="token comment"># Push the commit to the remote repository</span>

<span class="token function">git</span> push origin main
</code></pre>
<h1 id="wagtail">WAGTAIL</h1>
<h3 id="how-to-use-streamfield-for-mixed-content"><a href="https://docs.wagtail.org/en/v5.2.1/topics/streamfield.html">How to use StreamField for mixed content</a></h3>
<hr>
<h3 id="streamfield-block-reference"><a href="https://docs.wagtail.org/en/v5.2.1/reference/streamfield/blocks.html#streamfield-block-reference">StreamField block reference</a></h3>
<h3 id="templating---jinja"><a href="https://docs.wagtail.org/en/v5.2.2/reference/jinja2.html">Templating - Jinja</a></h3>
<h4 id="wrinting-templates"><a href="https://docs.wagtail.org/en/v5.2.2/topics/writing_templates.html#writing-templates">Wrinting Templates</a></h4>
<p>La regola da seguire è questa:</p>
<p><span><code>code: class wagtail.fields.StreamField(blocks, use_json_field=None, blank=False, min_num=None, max_num=None, block_counts=None, collapsed=False)</code></span></p>
<p>E questa la spiegazione:</p>
<p><strong>class wagtail.fields.StreamField</strong>: This line defines a class named StreamField in the wagtail.fields module.</p>
<p><strong>(blocks, use_json_field=None, blank=False, min_num=None, max_num=None, block_counts=None, collapsed=False)</strong>: These are the parameters that the StreamField class constructor (<strong>init</strong> method) accepts. Let’s go through each one:</p>
<p><strong>blocks</strong>: This is a required parameter. It represents the blocks that can be used in the stream. It seems like it should be provided when creating an instance of StreamField.</p>
<p><strong>use_json_field</strong>=None: This is an optional parameter with a default value of None. It allows you to specify whether to use a JSON field for storage. If not provided, it defaults to None.</p>
<p><strong>blank</strong>=False: This is an optional parameter with a default value of False. It indicates whether the field is allowed to be blank when used in a form. If not provided, it defaults to False.</p>
<p><strong>min_num</strong>=None: This is an optional parameter with a default value of None. It specifies the minimum number of blocks required. If not provided, it defaults to None.</p>
<p><strong>max_num</strong>=None: This is an optional parameter with a default value of None. It specifies the maximum number of blocks allowed. If not provided, it defaults to None.</p>
<p><strong>block_counts</strong>=None: This is an optional parameter with a default value of None. It seems related to counting blocks. If not provided, it defaults to None.</p>
<p><strong>collapsed</strong>=False: This is an optional parameter with a default value of False. It indicates whether the blocks should be collapsed in the Wagtail admin interface. If not provided, it defaults to False</p>
<p>Così ad esempio per questo codice. Possiamo effettuare il breakdown di questo codice in base alla regola definita:</p>
<p>`class BlogPage(Page):<br>
author = models.CharField(max_length=255, default=‘Default Author’)<br>
date = models.DateField(“Post date”)</p>
<pre><code>body = StreamField(
    [
        ('heading', blocks.CharBlock(form_classname="title")),
        ('paragraph', blocks.RichTextBlock()),
        ('image', ImageChooserBlock()),
        ('code', CodeBlock()),
        ('raw_html', RawHTMLBlock()),
    ],
    use_json_field=True
)

content_panels = Page.content_panels + [
    FieldPanel('author'),
    FieldPanel('date'),
    FieldPanel('body'),
]
</code></pre>
<p>`</p>
<p><strong>author</strong> = models.CharField(max_length=255, default=‘Default Author’): This line defines a character field named author in the BlogPage class. It has a maximum length of 255 characters and a default value of ‘Default Author’.</p>
<p><strong>date</strong> = models.DateField(“Post date”): This line defines a date field named date in the BlogPage class with a human-readable name “Post date”.</p>
<p><strong>body</strong> = StreamField([…], use_json_field=True): This line defines a stream field named body in the BlogPage class. It allows the inclusion of different block types, such as CharBlock, RichTextBlock, ImageChooserBlock, CodeBlock, and RawHTMLBlock. <strong>The use_json_field parameter is set to True, indicating that a JSON field will be used for storage.</strong></p>
<p><strong>content_panels</strong> = Page.content_panels + […]: This line defines the content panels for the Wagtail admin interface. It includes panels for ‘author’, ‘date’, and ‘body’.</p>
<p>Poi in particolare:</p>
<h2 id="content_panels-definition-in-the-blogpage-class">content_panels definition in the BlogPage class:</h2>
<p><code>content_panels = Page.content_panels + [ FieldPanel('author'), FieldPanel('date'), FieldPanel('body'), ]</code></p>
<p><strong>Page.content_panels</strong>: This part includes the content panels defined in the parent Page class. It allows the inclusion of standard page fields, such as title, slug, publish date, etc.</p>
<p><strong>FieldPanel(‘author’)</strong>: This adds a panel for the author field to the content panels. It’s likely a simple text input for the author’s name.</p>
<p><strong>FieldPanel(‘date’)</strong>: This adds a panel for the date field, probably a date picker for selecting the post date.</p>
<p><strong>FieldPanel(‘body’)</strong>: This adds a panel for the body field. Since it’s a StreamField, it might include a dynamic set of blocks like headings, paragraphs, images, code blocks, and raw HTML.</p>
<h2 id="uso-dello-structbox-in-wagtail">Uso dello StructBox in Wagtail</h2>
<p>Example Model with StructBlock<br>
Consider a simple model for a page with a StreamField containing a StructBlock named ‘person’:</p>
<p><span>` # <a href="http://models.py">models.py</a><br>
from django.db import models<br>
from wagtail.core.fields import StreamField<br>
from wagtail.core import blocks<br>
from wagtail.images.blocks import ImageChooserBlock<br>
from wagtail.core.models import Page<br>
from wagtail.admin.edit_handlers import FieldPanel, StreamFieldPanel</span></p>
<p>class BlogPage(Page):<br>
body = StreamField([<br>
(‘person’, blocks.StructBlock([<br>
(‘first_name’, blocks.CharBlock()),<br>
(‘surname’, blocks.CharBlock()),<br>
(‘photo’, ImageChooserBlock(required=False)),<br>
(‘biography’, blocks.RichTextBlock()),<br>
])),<br>
(‘heading’, blocks.CharBlock(form_classname=“title”)),<br>
(‘paragraph’, blocks.RichTextBlock()),<br>
(‘image’, ImageChooserBlock()),<br>
], use_json_field=True)</p>
<pre><code>content_panels = Page.content_panels + [
    StreamFieldPanel('body'),
] `&lt;/span&gt;
</code></pre>
<p>Diagram Explanation<br>
Blog Page with StreamField and StructBlock:</p>
<p>A BlogPage contains a StreamField named ‘body’.<br>
‘body’ includes various block types, one of which is a StructBlock named ‘person’.<br>
Person StructBlock:</p>
<p>The ‘person’ block is a StructBlock containing fields like ‘first_name’, ‘surname’, ‘photo’, and ‘biography’.<br>
Block Instances:</p>
<p>When editing a BlogPage, you can add multiple instances of different block types, including ‘person’. Each ‘person’ block instance can have its own ‘first_name’, ‘surname’, ‘photo’, and ‘biography’</p>
<p><em><strong>Template Implementation</strong></em></p>
<p>To render this in a template, you can use the following:</p>
<pre><code>`&lt;!-- templates/blog_page.html --&gt;
{% extends "base.html" %}

{% block content %}
    &lt;article&gt;
        {% for block in page.body %}
            {% if block.block_type == 'person' %}
                &lt;div class="person"&gt;
                    {% if block.value.photo %}
                        {% image block.value.photo width-400 %}
                    {% endif %}
                    &lt;h2&gt;{{ block.value.first_name }} {{ block.value.surname }}&lt;/h2&gt;
                    {{ block.value.biography }}
                &lt;/div&gt;
            {% else %}
                {# Rendering for other block types #}
                &lt;section class="{{ block.block_type }}"&gt;
                    {% include_block block %}
                &lt;/section&gt;
            {% endif %}
        {% endfor %}
    &lt;/article&gt;
{% endblock %} 
</code></pre>
<hr>
<p><em><strong>Database Initialization</strong></em></p>
<p>When you run makemigrations and migrate after adding the StructBlock to your model, the necessary database tables and fields are created. The use_json_field=True parameter in the StreamField indicates that the data for the StreamField will be stored as JSON in the database.</p>
<p>Here’s how you perform the migration:</p>
<p>bash<br>
Copy code<br>
python <a href="http://manage.py">manage.py</a> makemigrations<br>
python <a href="http://manage.py">manage.py</a> migrate<br>
After migration, you can create or edit a BlogPage instance through the Wagtail admin interface. The StructBlock fields will be part of the form for each ‘person’ block within the ‘body’ StreamField.</p>
<h3 id="riferimenti-rapidi-wagtail">Riferimenti Rapidi Wagtail</h3>
<ul>
<li><a href="https://www.outreachy.org/docs/internship/">Caso Studio web page</a></li>
<li><a href="https://docs.wagtail.org/en/v5.2.1/topics/streamfield.html">How to use Streamfield for mixed content</a></li>
<li><a href="https://docs.wagtail.org/en/v5.2.1/reference/streamfield/blocks.html#streamfield-block-reference">StreamFieldBlock Reference</a></li>
<li></li>
</ul>
<h2 id="caratteristiche-avanzate-di-diango---wagtail">Caratteristiche avanzate di Diango - Wagtail</h2>
<p>Uno dei porblemi che si incontrano effettuando delle tabelle all’interno di wagtail ma in generale anche in Django è il caso pratico della renderizzazione degli headers di una tabella se si vogliono recuperare ad esempio i dati all’interno delle celle della tabella.</p>
<p>Questo codice di esempio effettua il debug su ciò che è successo:</p>
<p>`<br>
<br>
{% for column in block.value.columns %}<br>
<br>
{{ column.header|default:“Column Header” }}</p>
<pre><code>            &lt;!-- Debugging statements --&gt;
            &lt;p&gt;block.value.rows: {{ block.value.rows|list }}&lt;/p&gt;
            &lt;p&gt;block.value.rows.1: {{ block.value.rows|list.1|default:"" }}&lt;/p&gt;
            
            {% with block.value.rows|list.1|default:"" as row_values %}
                {{ row_values.0|default:"" }}
            {% endwith %}
        &lt;/th&gt;
    {% endfor %}
&lt;/tr&gt;
</code></pre>

`
Un estratto di codice generato è questo 
`   <table id="datatable_1" class="display nowrap datatable">
                        <thead>
                            <tr>

</tr></thead></table><pre><code>                                &lt;th&gt;
                                    Column Header
                                    
                                    &lt;!-- Debugging statements --&gt;
                                    &lt;p&gt;block.value.rows: &amp;lt;generator object TypedTable.rows at 0x7f08958de2e0&amp;gt;&lt;/p&gt;
                                    &lt;p&gt;block.value.rows.1: &lt;/p&gt; `
</code></pre>
                    
                    <p>Approfondendo la ricerca si artriva a tale indicazione<br>
:::caution<br>
The issue seems to be related to the fact that block.value.rows is a generator object. In Python, generators are lazy and can be consumed only once. If you try to iterate through the generator more than once, you will get an empty result on subsequent iterations.</p>
<p>In your case, it seems like the generator has been consumed once, which is why when you try to access block.value.rows.1, it doesn’t contain any values.</p>
<p>To address this issue, you might want to convert the generator to a list so that you can iterate through it multiple times. However, since you are using the TypedTableBlock from wagtail.contrib.typed_table_block, you might need to adjust how you access the rows.</p>
<p>Here is a modification that converts the generator to a list before using it:</p>
<p>django<br>
Copy code</p>

    
        {% for column in block.value.columns %}
            
                {{ column.header|default:"Column Header" }}
<pre><code>            &lt;!-- Debugging statements --&gt;
            &lt;p&gt;block.value.rows: {{ block.value.rows|list }}&lt;/p&gt;
            &lt;p&gt;block.value.rows.1: {{ block.value.rows|list.1|default:"" }}&lt;/p&gt;
            
            {% with block.value.rows|list.1|default:"" as row_values %}
                {{ row_values.0|default:"" }}
            {% endwith %}
        &lt;/th&gt;
    {% endfor %}
&lt;/tr&gt;
</code></pre>

This uses the |list filter to convert the generator to a list before accessing the second row. Please note that this might not be the most efficient solution, especially if your table has a large number of rows. If efficiency is a concern, you may want to explore other ways to handle this situation.
:::
<h2 id="wagtail-upgrade-process">WAGTAIL Upgrade process</h2>
<p>We recommend upgrading one feature release at a time, even if your project is several versions behind the current one. This has a number of advantages over skipping directly to the newest release:</p>
<p>If anything breaks as a result of the upgrade, you will know which version caused it, and will be able to troubleshoot accordingly;</p>
<p>Deprecation warnings shown in the console output will notify you of any code changes you need to make before upgrading to the following version;</p>
<p>Some releases make database schema changes that need to be reflected on your project by running ./manage.py makemigrations - this is liable to fail if too many schema changes happen in one go.</p>
<p>Before upgrading to a new feature release:</p>
<p>Check your project’s console output for any deprecation warnings, and fix them where necessary;</p>
<p>Check the new version’s release notes, and the Compatible Django / Python versions table below, for any dependencies that need upgrading first;</p>
<p>Make a backup of your database.</p>
<p>To upgrade:</p>
<p>Update the wagtail line in your project’s requirements.txt file to specify the latest patch release of the version you wish to install. For example, to upgrade to version 1.8.x, the line should read:<br>
`wagtail&gt;=1.8,&lt;1.9<br>
Run:</p>
<p>pip install -r requirements.txt<br>
./manage.py makemigrations<br>
./manage.py migrate`</p>
<p>Make any necessary code changes as directed in the “Upgrade considerations” section of the release notes.</p>
<p>Test that your project is working as expected.</p>
<p>Remember that the JavaScript and CSS files used in the Wagtail admin may have changed between releases - if you encounter erratic behaviour on upgrading, ensure that you have cleared your browser cache. When deploying the upgrade to a production server, be sure to run ./manage.py collectstatic to make the updated static files available to the web server. In production, we recommend enabling ManifestStaticFilesStorage in the STATICFILES_STORAGE setting - this ensures that different versions of files are assigned distinct URLs.</p>
<h3 id="wagtail-compatibility-with-django---link">WAGTAIL COMPATIBILITY WITH DJANGO - <a href="https://docs.wagtail.org/en/latest/releases/upgrading.html">link</a></h3>
<h1 id="python">PYTHON</h1>
<h2 id="spiegazione-attraverso-codice-di-init-getattribute-e-super">Spiegazione attraverso codice di <strong>init</strong>, <strong>getattribute</strong> e super</h2>
<p>Spesso nei moduli di wagtail si fa riferimento alla classazione e subclassazione. Avere chiri alcuni termini è necessario. Questa è la breve sintesi attraverso un sempio</p>
<p><code>class Vehicle: def</code><strong>init</strong>(self, brand):<br>
self.brand = brand</p>
<pre><code>def start(self):
    print(f"{self.brand} vehicle started.")`
</code></pre>
<p>This is a simple class representing a vehicle with a brand.<br>
It has an <strong>init</strong> method that initializes the brand attribute and a start method to print a message when the vehicle starts.<br>
Car (inherits from Vehicle):</p>
<p>python<br>
Copy code<br>
class Car(Vehicle):<br>
def <strong>init</strong>(self, brand, model):<br>
# No use of super()<br>
​        self.model = model</p>
<pre><code>def start(self):
    print(f"{self.brand} {self.model} car started.")
</code></pre>
<p>This class represents a specific type of vehicle, a Car, inheriting from the Vehicle class.<br>
It has its own <strong>init</strong> method, but it doesn’t use super(), and it has a start method that overrides the start method in the Vehicle class.<br>
CarWithSuper (inherits from Car):</p>
<p>class CarWithSuper(Car):<br>
def <strong>init</strong>(self, brand, model, color):<br>
super().<strong>init</strong>(brand, model)<br>
self.color = color</p>
<pre><code>def start(self):
    super().start()
    print(f"The {self.color} car is ready to go.")

def __getattribute__(self, name):
    # Modifying __getattribute__ to add a prefix to the brand attribute
    if name == "brand":
        return "Awesome " + super().__getattribute__(name)
    else:
        return super().__getattribute__(name)
</code></pre>
<p>This class inherits from Car and introduces a new attribute color.<br>
It uses super() in the <strong>init</strong> method to call the <strong>init</strong> method of the parent class (Car).<br>
It overrides the start method, calls the parent’s start method using super(), and adds an additional message.<br>
It also modifies <strong>getattribute</strong> to add a prefix (“Awesome”) to the brand attribute.<br>
Examples:<br>
Example without super(), <strong>init</strong>, and <strong>getattribute</strong>:</p>
<p><code>car_without_super = Car(brand="Toyota", model="Camry") print(car_without_super.model) # Output: Camry An instance of Car is created without using super(). __init__ in Car is called, but __init__ of the parent (Vehicle) is not called. start method from Vehicle is not available in car_without_super. Example with super(), __init__, and __getattribute__: car_with_super = CarWithSuper(brand="Ford", model="Mustang", color="red") print(car_with_super.brand) # Output: Awesome Ford car_with_super.start() # Output: Ford Mustang car started. The red car is ready to go.</code></p>
<p>An instance of CarWithSuper is created using super() to call <strong>init</strong> of the parent (Car).<br>
<strong>getattribute</strong> is modified to add a prefix to the brand attribute.<br>
start method calls the parent’s (Car) start method using super() and adds an additional message.<br>
Roles:</p>
<p><em><strong><strong>init</strong>:</strong></em><br>
Used for initializing the attributes of an object.<br>
In the inheritance chain, it’s common to use super().<strong>init</strong>(…) to call the initializer of the parent class.</p>
<p><em><strong><strong>getattribute</strong>:</strong></em> Called whenever an attribute of an object is accessed.<br>
Can be modified to customize attribute access.<br>
Used here to modify the behavior of accessing the brand attribute.</p>
<p><em><strong>super():</strong></em> Used to refer to the parent class.<br>
In <strong>init</strong>, it’s used to call the initializer of the parent class.<br>
In methods, it’s used to call methods from the parent class.<br>
In the provided example, super() helps maintain the hierarchy in inheritance, ensuring that the methods of the parent classes are appropriately called. <strong>init</strong> is used for object initialization, and <strong>getattribute</strong> is modified to customize attribute access.</p>
<h3 id="vediamo-ora-cosa-succede-se-non-utilizziamo-i-metodi">Vediamo ora cosa succede se non utilizziamo i metodi</h3>
<h3 id="assenza-di-init">Assenza di <strong>init</strong></h3>
<p>If you don’t use the <strong>init</strong> method in the Vehicle class, the class will still be valid, but instances of the class won’t have a constructor to initialize their state. The <strong>init</strong> method is a special method in Python classes that is automatically called when an object is created. It is used for initializing the attributes of the object.</p>
<p>Here’s what happens when you don’t include <strong>init</strong>:</p>
<p>python<br>
Copy code<br>
class Vehicle:<br>
def start(self):<br>
print(“Vehicle started.”)</p>
<h3 id="creating-an-instance-without-init">Creating an instance without <strong>init</strong></h3>
<p>vehicle_instance = Vehicle()</p>
<h3 id="this-will-not-raise-an-error-but-the-instance-wont-have-a-brand-attribute.">This will not raise an error, but the instance won’t have a ‘brand’ attribute.</h3>
<h3 id="if-you-try-to-access-brand-it-will-result-in-an-attributeerror.">If you try to access ‘brand’, it will result in an AttributeError.</h3>
<p>print(vehicle_instance.start())  # Output: Vehicle started.<br>
print(vehicle_instance.brand)  # AttributeError: ‘Vehicle’ object has no attribute ‘brand’<br>
In the example above, creating an instance of Vehicle without an <strong>init</strong> method is allowed. However, without an <strong>init</strong> method, instances won’t have any attributes initialized during instantiation. If you try to access an attribute that hasn’t been defined, you will get an AttributeError.</p>
<p>Including the <strong>init</strong> method allows you to initialize the state of an object when it is created. For example:</p>
<p>python<br>
Copy code<br>
class Vehicle:<br>
def <strong>init</strong>(self, brand):<br>
self.brand = brand</p>
<pre><code>def start(self):
    print(f"{self.brand} vehicle started.")
</code></pre>
<h3 id="creating-an-instance-with-init">Creating an instance with <strong>init</strong></h3>
<p>vehicle_instance = Vehicle(brand=“Toyota”)</p>
<p><code>Now, the 'brand' attribute is initialized during instantiation.</code><br>
print(vehicle_instance.start())  # Output: Toyota vehicle started.<br>
print(vehicle_instance.brand)  # Output: Toyota<br>
In the second example, the <strong>init</strong> method is used to initialize the brand attribute when a Vehicle instance is created. This ensures that the instance has a properly initialized state from the beginning.</p>
<h2 id="ed-ora-quando-posso-usare-e-non-usare-getattribute">Ed ora quando posso usare e non usare <strong>getattribute</strong>?</h2>
<p>If you don’t define the <strong>getattribute</strong> method in a class, Python will use the default behavior for attribute access. The default behavior involves looking up the attribute in the object’s dictionary and returning its value if found. If the attribute is not found in the object’s dictionary, Python looks for the attribute in the class hierarchy.</p>
<p>Here’s what happens if you don’t use <strong>getattribute</strong>:</p>
<p>python<br>
Copy code<br>
class Vehicle:<br>
def <strong>init</strong>(self, brand):<br>
self.brand = brand</p>
<pre><code>def start(self):
    print(f"{self.brand} vehicle started.")
</code></pre>
<h2 id="creating-an-instance-without-getattribute">Creating an instance without <strong>getattribute</strong></h2>
<p>vehicle_instance = Vehicle(brand=“Toyota”)</p>
<h3 id="accessing-the-brand-attribute-without-a-custom-getattribute">Accessing the ‘brand’ attribute without a custom <strong>getattribute</strong></h3>
<p>print(vehicle_instance.brand)  # Output: Toyota</p>
<h3 id="the-default-behavior-is-used-and-there-is-no-need-for-a-custom-getattribute-in-this-case.">The default behavior is used, and there is no need for a custom <strong>getattribute</strong> in this case.</h3>
<p>In the example above, we create a Vehicle class with an <strong>init</strong> method to initialize the brand attribute. When we access the brand attribute, the default attribute access behavior is used, and there is no need for a custom <strong>getattribute</strong>. The attribute is found in the instance’s dictionary, and its value is returned.</p>
<p>The <strong>getattribute</strong> method is a powerful tool for customizing attribute access, and it allows you to intercept attribute access calls and customize the behavior. However, in many cases, you may not need to override it, and the default behavior is sufficient for basic attribute access. Only when you need to customize the attribute access behavior should you consider defining a <strong>getattribute</strong> method.</p>
<p>In the example provided, the <strong>getattribute</strong> method is used to customize the behavior of accessing the brand attribute in the CarWithSuper class. Specifically, it adds a prefix (“Awesome”) to the value of the brand attribute before returning it.</p>
<p>Here’s the relevant part of the code:</p>
<p>python<br>
Copy code<br>
class CarWithSuper(Car):<br>
# …</p>
<pre><code>def __getattribute__(self, name):
    # Modifying __getattribute__ to add a prefix to the brand attribute
    if name == "brand":
        return "Awesome " + super().__getattribute__(name)
    else:
        return super().__getattribute__(name)
</code></pre>
<p>In this case, the <strong>getattribute</strong> method is modifying the behavior of accessing the brand attribute. Without this customization, accessing car_with_super.brand would simply return the value of the brand attribute. With the custom <strong>getattribute</strong>, it returns the value with the added prefix.</p>
<p>So, you might need to use <strong>getattribute</strong> when you want to customize or intercept attribute access calls and modify the behavior based on your specific requirements. It’s a powerful tool, but it should be used judiciously, as unnecessary or incorrect use may lead to unexpected behavior and potential issues.</p>
<h2 id="mixin">MIXIN</h2>
<p>L’esempio esposto e che di seguito si ripropone risulta anche un ottimo esempio di mixin</p>
<p>Yes, the provided example with Vehicle, Car, and CarWithSuper can be considered an example of mixin-like behavior. Let me break it down:</p>
<p>Vehicle Class:</p>
<p>python<br>
Copy code<br>
class Vehicle:<br>
def <strong>init</strong>(self, brand):<br>
self.brand = brand</p>
<pre><code>def start(self):
    print(f"{self.brand} vehicle started.")
</code></pre>
<p>This is the base class representing a generic vehicle. It has an <strong>init</strong> method to initialize the brand attribute and a start method.</p>
<p>Car Class (Inherits from Vehicle):</p>
<p>python<br>
Copy code<br>
class Car(Vehicle):<br>
def <strong>init</strong>(self, brand, model):<br>
super().<strong>init</strong>(brand)<br>
self.model = model</p>
<pre><code>def start(self):
    print(f"{self.brand} {self.model} car started.")
</code></pre>
<p>The Car class inherits from Vehicle. It has its own <strong>init</strong> method but uses super() to call the <strong>init</strong> method of the parent class (Vehicle). It also has its own start method, overriding the start method of Vehicle.</p>
<p>CarWithSuper Class (Inherits from Car):</p>
<p>python<br>
Copy code<br>
class CarWithSuper(Car):<br>
def <strong>init</strong>(self, brand, model, color):<br>
super().<strong>init</strong>(brand, model)<br>
self.color = color</p>
<pre><code>def start(self):
    super().start()
    print(f"The {self.color} car is ready to go.")

def __getattribute__(self, name):
    if name == "brand":
        return "Awesome " + super().__getattribute__('brand')
    else:
        return super().__getattribute__(name)
</code></pre>
<p>The CarWithSuper class inherits from Car and introduces a new attribute (color). It uses super() to call the <strong>init</strong> method of the parent class (Car). It also overrides the start method, calling the parent’s (Car) start method using super() and adding an additional message. Additionally, it modifies <strong>getattribute</strong> to add a prefix (“Awesome”) to the brand attribute.</p>
<p>So, in this example, the classes are organized in a way that exhibits mixin-like behavior. The CarWithSuper class enhances the behavior of the Car class by adding attributes and modifying methods, and it uses super() to maintain the hierarchy and call methods from parent classes. While it may not strictly adhere to the classic definition of a mixin, it shares some characteristics of mixin-like behavior.</p>
<h3 id="definizione-di-mixin">Definizione di mixin</h3>
<p>In object-oriented programming, a mixin is a class that provides a certain functionality to be inherited by a subclass, but is not meant to stand alone. Mixins are used to enhance the functionality of a class without the need for multiple inheritance.</p>
<p>Here are some key characteristics and features of mixins:</p>
<p>Purpose-Specific Functionality: Mixins are designed to provide a specific set of functionalities or behaviors that can be easily added to other classes. They encapsulate a piece of behavior.</p>
<p>Reusability: Mixins promote code reuse. Instead of duplicating code in multiple classes, you can create a mixin and include it in various classes that need that particular behavior.</p>
<p>No Standalone Use: Mixins are not meant to be instantiated or used independently. They lack the complete implementation to be used as standalone classes. They are intended to be combined with other classes.</p>
<p>Flexible Composition: Since a class can inherit from multiple mixins, it allows for flexible composition of functionalities. This is in contrast to languages that do not support multiple inheritance directly.</p>
<p>Avoids Diamond Problem: Mixins can help avoid the “diamond problem” that arises in languages with multiple inheritance, where a class inherits from two classes that have a common ancestor.</p>
<p>Small and Focused: Mixins are typically small and focused on a specific task. This makes them easy to understand, maintain, and reuse.</p>
<h1 id="standard-commands-in-django-installation">STANDARD COMMANDS IN DJANGO INSTALLATION#</h1>
<ol>
<li>python3 -m venv venv</li>
</ol>
<h1 id="useful-property-and-method-in-django">USEFUL PROPERTY AND METHOD IN DJANGO</h1>
<h2 id="luso-di-queryset">L’uso di Queryset</h2>
<p>Django querysets have several notable properties and methods that provide flexibility and ease of use when interacting with the database. Here are some key properties and methods of querysets:</p>
<p>Chaining:</p>
<p>Querysets are lazy, meaning they don’t hit the database until an action is performed.<br>
Multiple filters and operations can be chained together to build complex queries.<br>
Example:</p>
<p>python<br>
Copy code<br>
queryset = Model.objects.filter(field1=value1).exclude(field2=value2).order_by(’-date_created’)<br>
Slicing:</p>
<p>Querysets can be sliced to retrieve a specific range of objects.<br>
Example:</p>
<p>python<br>
Copy code<br>
queryset = Model.objects.all()<br>
result_slice = queryset[5:10]  # Retrieve objects 5 through 9<br>
Count:</p>
<p>The count method returns the number of objects in the queryset without fetching the actual objects.<br>
Example:</p>
<p>python<br>
Copy code<br>
count = queryset.count()<br>
Distinct:</p>
<p>The distinct method eliminates duplicate rows from the queryset.<br>
Example:</p>
<p>python<br>
Copy code<br>
distinct_values = Model.objects.values(‘field’).distinct()<br>
Aggregate:</p>
<p>The aggregate method allows for the calculation of aggregate values (e.g., sum, average) on the queryset.<br>
Example:</p>
<p>python<br>
Copy code<br>
from django.db.models import Avg<br>
average_value = Model.objects.aggregate(avg_value=Avg(‘numeric_field’))<br>
Values and ValuesList:</p>
<p>The values method returns a queryset of dictionaries representing the values of specific fields.<br>
The values_list method returns a queryset of tuples representing the values of specific fields.<br>
Example:</p>
<p>python<br>
Copy code<br>
values_queryset = Model.objects.values(‘field1’, ‘field2’)<br>
values_list_queryset = Model.objects.values_list(‘field1’, ‘field2’)<br>
Exists:</p>
<p>The exists method checks if there are any records in the queryset.<br>
Example:</p>
<p>queryset_exists = Model.objects.filter(field=value).exists()<br>
Update and Delete:</p>
<p>The update method modifies multiple records in the database without fetching them.<br>
The delete method deletes records from the database without fetching them.<br>
Example:</p>
<p>python<br>
Copy code<br>
Model.objects.filter(field=value).update(status=‘new_status’)<br>
Model.objects.filter(field=value).delete()<br>
These are just a few of the many properties and methods provided by Django querysets. They offer a powerful and expressive way to interact with the database.</p>
<h3 id="esempio-in-wagtail">Esempio in wagtail</h3>
<p>from datetime import datetime, timedelta, timezone<br>
from django.shortcuts import render<br>
from wagtail.core.models import Page<br>
from your_app.models import RoundPage  # Replace ‘your_app’ with the actual name of your app<br>
from path.to.get_deadline_date_for import get_deadline_date_for  # Replace ‘<a href="http://path.to">path.to</a>’ with the actual path</p>
<p>def docs_internship(request):<br>
now = datetime.now(timezone.utc)<br>
today = get_deadline_date_for(now)<br>
five_weeks_ago = today - timedelta(days=7 * 5)</p>
<pre><code>applicant_round = RoundPage.objects.filter(
    pingnew__lte=today,
    internannounce__gt=today,
).first()

intern_round = RoundPage.objects.filter(
    internannounce__lte=today,
    internends__gt=five_weeks_ago,
).first()

return render(request, 'home/docs/internship_guide.html', {
    'applicant_round': applicant_round,
    'intern_round': intern_round,
})
</code></pre>
<h1 id="git--github-1">GIT &amp; GITHUB</h1>
<p>Riferimenti <a href="https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax">Mastering MarkDown</a></p>
<h3 id="ricordarsi-di-aggiungere-.gitgnore-1">Ricordarsi di aggiungere .gitgnore</h3>
<p><strong>- git add .gitignore</strong><br>
<strong>- git commit -m "Add .gitignore to exclude compiled Python files"</strong></p>
<h3 id="per-effettuare-il-push-da-origine-a-remoto-1">Per effettuare il push da origine a remoto</h3>
<p><strong>- git push origin implementazione-pagina</strong></p>
<h3 id="switch-to-the-new-branch-1">Switch to the New Branch:</h3>
<p><strong>- git checkout new-branch-name</strong></p>
<h3 id="creare-una-nuova-branch-e-posizionarsi-sulla-stessa-1">Creare una nuova branch e posizionarsi sulla stessa</h3>
<h2 id="git-checkout--b-new-branch-name"><strong>- git checkout -b new-branch-name</strong></h2>
<h2 id="il-comando-può-essere-visto-come-la-sintesi-dei-due-seguenti-comandi"><em>Il comando può essere visto come la sintesi dei due seguenti comandi:</em></h2>
<p><strong>- git branch new-branch-name  # Create a new branch</strong><br>
<strong>- git checkout new-branch-name  # Switch to the new branch</strong></p>
<h2 id="youve-created-a-new-branch-template-tutorial-without-committing-changes-on-your-existing-branch-implementazione-pagina-1">You’ve created a new branch (template-tutorial) without committing changes on your existing branch (implementazione-pagina)</h2>
<p>To address this, you’ll need to follow these steps to commit your changes on the implementazione-pagina branch and then switch back to the template-tutorial branch. Here’s a step-by-step guide:</p>
<ul>
<li>Commit Changes on implementazione-pagina:<br>
Assuming you are currently on the template-tutorial branch, ** switch back to the implementazione-pagina branch:**</li>
</ul>
<p><code>git checkout implementazione-pagina</code></p>
<p>Now, add and commit your changes:</p>
<p><code>git add .</code><br>
<code>git commit -m "Your commit message here"</code></p>
<ul>
<li><strong>Push Changes to Remote (implementazione-pagina):</strong><br>
Assuming the remote branch is named implementazione-pagina:</li>
</ul>
<p><code>git push origin implementazione-pagina</code></p>
<ul>
<li>** Switch Back to template-tutorial:**<br>
Now, switch back to the template-tutorial branch:</li>
</ul>
<p><code>git checkout template-tutorial</code></p>
<p>*** If you haven’t pushed the template-tutorial branch yet, you can push it to the remote repository when you’re ready:***</p>
<p><code>git push origin template-tutorial</code></p>
<p>*** How can see from my vsc local if a git branch is present also in the remote github? ***</p>
<p><code>git fetch --all git branch -a</code><br>
This fetches all branches from the remote repository and lists both local and remote branches. Remote branches are prefixed with “remotes/origin/”. Check if your branch is listed among the remotes.</p>
<p>*** Come posso creare una nuova branch in local, e poi crearla anche in Github, poi effettuare il push e rendere questa branch principale? ***</p>
<p>Create a new branch locally and switch to it (chimiamo la nuova branch template-tutorial):<br>
<code>git checkout -b template-tutorial</code></p>
<p>Push the new branch to GitHub - *** If you want to make sure that the new branch on GitHub exactly matches your local branch, you can use the -u (or --set-upstream) option when pushing for the first time ***</p>
<p><code>git push -u origin template-tutorial</code></p>
<p>Set the upstream for the new branch:</p>
<p><code>git branch --set-upstream-to=origin/template-tutorial template-tutorial</code>![alt]( ‘{“class”: “”, “title”: “”}’)</p>
<p>Now, further pushes can be simplified to:</p>
<p><code>git push</code></p>
<p>To revert the changes and go back to the original commit before the changes, you can use the following commands:<br>
<code>git reset --hard HEAD git clean -fd</code></p>
<p>The first command (git reset --hard HEAD) resets your branch to the latest commit, discarding changes. The second command (git clean -fd) removes untracked files and directories. Use them with caution, as they are not reversible.</p>
<p>-fd stands for what?<br>
In the context of the git clean command:</p>
<p>-f stands for force.<br>
-d stands for directory.<br>
Together, -fd means force removal of untracked directories. This option is used to remove untracked files and directories forcefully.</p>
<h2 id="delete-a-local-branch-and-also-delete-it-on-the-remote-repository-on-github-1">delete a local branch and also delete it on the remote repository on GitHub</h2>
<p>Delete the local branch:</p>
<p><code>git branch -d branch_name</code>![alt]( ‘{“class”: “”, “title”: “”}’)</p>
<p>Replace branch_name with the name of the branch you want to delete.</p>
<p>If the branch contains unmerged changes, you might need to force delete it:</p>
<p><code>git branch -D branch_name</code></p>
<p>Delete the remote branch:</p>
<p><code>git push origin --delete branch_name</code></p>
<p>This will delete the branch on the remote repository (GitHub).</p>
<p>Update your local repository to reflect the changes on the remote:</p>
<p><code>git fetch --prune</code></p>
<p>The --prune flag removes any remote tracking branches that no longer exist on the remote.</p>
<h2 id="i-want-to-synch-another-an-oldest-branch-named-template-tutorial-with-a-newest-branch-named-template-sheetlike-and-after-delete-this-last-one-template-sheetlike-1">I want to synch another an oldest branch named “template-tutorial” with a newest branch named template-sheetlike and after delete this last one (template-sheetlike)</h2>
<p>Switch to the template-tutorial branch:<br>
<code>git switch template-tutorial</code></p>
<p>Rebase template-sheetlike onto template-tutorial:<br>
<code>git rebase template-sheetlike</code></p>
<p>Push the changes to the remote repository:<br>
<code>git push origin template-tutorial --force</code><br>
Note: Force-pushing after a rebase rewrites the commit history. Use it with caution, especially if the branch has already been shared with others</p>
<p>Delete the template-sheetlike branch:<br>
<code>git branch -d template-sheetlike</code><br>
<code>git push origin --delete template-sheetlike</code></p>
<h3 id="some-useful-notes-1">some useful notes</h3>
<p>Merge:<br>
Creates Merge Commits: When you merge one branch into another, Git creates a new merge commit that has two parent commits: <strong>one from the branch you’re merging and another from the branch you’re merging into.<br>
This results in a non-linear history with multiple branches merging into each other</strong><br>
Preserves Original History:</p>
<p>The original commits from both branches remain unchanged. This approach keeps a clear record of when changes were made on each branch.</p>
<h6 id="rebase">Rebase:</h6>
<p>Linearizes History:</p>
<p>Rebase is used to linearize the commit history. It moves or combines a sequence of commits to a new base commit.<br>
When you rebase one branch onto another, it effectively transplants the entire branch onto the tip of the other branch, creating a linear history.<br>
No Merge Commits:</p>
<p>Unlike merge, rebase doesn’t create additional merge commits.<br>
It can result in a cleaner, more linear history.<br>
When to Choose Each Approach:</p>
<h6 id="merge">Merge:</h6>
<p>Use merge when you want to preserve the original commit history, especially when collaborating with others.<br>
Good for feature branches and when you want to maintain a clear record of branch integration points.<br>
Rebase:</p>
<p>Use rebase when you want a clean, linear history and don’t mind rewriting commits.<br>
Useful for feature branches before merging into a shared branch to avoid unnecessary merge commits.<br>
Switch vs. Checkout:<br>
git switch is a more modern and user-friendly command introduced in recent versions of Git. It is designed specifically for branch switching. If you’re using a version of Git that supports git switch, you can replace git checkout with git switch:</p>
<h6 id="switching-branch">Switching Branch:</h6>
<p>git switch template-tutorial<br>
Both commands essentially do the same thing in this context, but git switch provides a clearer and more explicit syntax for branch-related operations. If your Git version supports it, feel free to use git switch instead of git checkout.</p>
<h1 id="yaml-protocol">YAML PROTOCOL</h1>
<p>YAML (YAML Ain’t Markup Language) is a human-readable data serialization format that is often used for configuration files and data exchange between languages with different data structures. In a YAML file, indentation is crucial, as it determines the structure of the data. Here are some details on writing YAML files:</p>
<h3 id="indentation">1. <strong>Indentation:</strong></h3>
<ul>
<li>YAML uses indentation to represent the structure of the data. Spaces are recommended for indentation (not tabs), and the number of spaces is significant. Typically, two spaces or four spaces are used for each level of indentation.</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml"><span class="token key atrule">codekey1</span><span class="token punctuation">:</span>
  <span class="token key atrule">key2</span><span class="token punctuation">:</span> value
  <span class="token key atrule">key3</span><span class="token punctuation">:</span>
    <span class="token punctuation">-</span> item1
    <span class="token punctuation">-</span> item2
</code></pre>
<h3 id="key-value-pairs">2. <strong>Key-Value Pairs:</strong></h3>
<ul>
<li>YAML uses a simple key-value format. Keys and values are separated by a colon, and the key-value pair is represented on a new line.</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml"><span class="token key atrule">codename</span><span class="token punctuation">:</span> John Doe
<span class="token key atrule">age</span><span class="token punctuation">:</span> <span class="token number">30</span>
</code></pre>
<h3 id="lists">3. <strong>Lists:</strong></h3>
<ul>
<li>Lists are represented using a hyphen followed by a space (<code>-</code>). Lists can contain any combination of values, and each item is indented under the list key.</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml"><span class="token key atrule">codefruits</span><span class="token punctuation">:</span>
  <span class="token punctuation">-</span> apple
  <span class="token punctuation">-</span> banana
  <span class="token punctuation">-</span> orange
</code></pre>
<h3 id="dictionaries-mappings">4. <strong>Dictionaries (Mappings):</strong></h3>
<ul>
<li>Dictionaries or mappings are represented using key-value pairs, and the key-value pairs are indented under the dictionary key.</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml">  <span class="token key atrule">name</span><span class="token punctuation">:</span> John Doe
  <span class="token key atrule">age</span><span class="token punctuation">:</span> <span class="token number">30</span>
</code></pre>
<h3 id="strings">5. <strong>Strings:</strong></h3>
<ul>
<li>Strings can be written without quotes. However, quotes are used when a string contains special characters or reserved words.</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml"><span class="token key atrule">message</span><span class="token punctuation">:</span> Hello<span class="token punctuation">,</span> World!
</code></pre>
<h3 id="multiline-strings">6. <strong>Multiline Strings:</strong></h3>
<ul>
<li>Multiline strings can be represented using the <code>|</code> or <code>&gt;</code> characters. The <code>|</code> preserves newlines, while <code>&gt;</code> folds newlines.</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml"><span class="token key atrule">codemultiline</span><span class="token punctuation">:</span> <span class="token punctuation">|</span><span class="token scalar string">
  This is a multiline
  string in YAML.</span>
</code></pre>
<h3 id="comments">7. <strong>Comments:</strong></h3>
<ul>
<li>Comments start with the <code>#</code> character and continue to the end of the line.</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml">code<span class="token comment"># This is a comment</span>
<span class="token key atrule">key</span><span class="token punctuation">:</span> value
</code></pre>
<h3 id="anchors-and-aliases">8. <strong>Anchors and Aliases:</strong></h3>
<ul>
<li>YAML supports anchors (<code>&amp;</code>) and aliases (<code>*</code>) for creating references to the same data in multiple places.</li>
</ul>
<pre class=" language-yaml"><code class="prism  language-yaml"><span class="token key atrule">codefirst</span><span class="token punctuation">:</span> <span class="token important">&amp;anchor_name</span> John Doe
<span class="token key atrule">second</span><span class="token punctuation">:</span> <span class="token important">*anchor_name</span>
</code></pre>
<p>These are some basic conventions for writing YAML files. Ensure that you are consistent with indentation, use proper syntax for key-value pairs, lists, and dictionaries, and pay attention to the structure of your YAML documents. Many programming languages and tools use YAML, and understanding its syntax is beneficial for working with various configurations and data files.</p>
<h1 id="wagtail-1">WAGTAIL</h1>
<h3 id="how-to-use-streamfield-for-mixed-content-1"><a href="https://docs.wagtail.org/en/v5.2.1/topics/streamfield.html">How to use StreamField for mixed content</a></h3>
<hr>
<h3 id="streamfield-block-reference-1"><a href="https://docs.wagtail.org/en/v5.2.1/reference/streamfield/blocks.html#streamfield-block-reference">StreamField block reference</a></h3>
<h3 id="templating---jinja-1"><a href="https://docs.wagtail.org/en/v5.2.2/reference/jinja2.html">Templating - Jinja</a></h3>
<h4 id="wrinting-templates-1"><a href="https://docs.wagtail.org/en/v5.2.2/topics/writing_templates.html#writing-templates">Wrinting Templates</a></h4>
<p>La regola da seguire è questa:</p>
<p><span><code>code: class wagtail.fields.StreamField(blocks, use_json_field=None, blank=False, min_num=None, max_num=None, block_counts=None, collapsed=False)</code></span></p>
<p>E questa la spiegazione:</p>
<p><strong>class wagtail.fields.StreamField</strong>: This line defines a class named StreamField in the wagtail.fields module.</p>
<p><strong>(blocks, use_json_field=None, blank=False, min_num=None, max_num=None, block_counts=None, collapsed=False)</strong>: These are the parameters that the StreamField class constructor (<strong>init</strong> method) accepts. Let’s go through each one:</p>
<p><strong>blocks</strong>: This is a required parameter. It represents the blocks that can be used in the stream. It seems like it should be provided when creating an instance of StreamField.</p>
<p><strong>use_json_field</strong>=None: This is an optional parameter with a default value of None. It allows you to specify whether to use a JSON field for storage. If not provided, it defaults to None.</p>
<p><strong>blank</strong>=False: This is an optional parameter with a default value of False. It indicates whether the field is allowed to be blank when used in a form. If not provided, it defaults to False.</p>
<p><strong>min_num</strong>=None: This is an optional parameter with a default value of None. It specifies the minimum number of blocks required. If not provided, it defaults to None.</p>
<p><strong>max_num</strong>=None: This is an optional parameter with a default value of None. It specifies the maximum number of blocks allowed. If not provided, it defaults to None.</p>
<p><strong>block_counts</strong>=None: This is an optional parameter with a default value of None. It seems related to counting blocks. If not provided, it defaults to None.</p>
<p><strong>collapsed</strong>=False: This is an optional parameter with a default value of False. It indicates whether the blocks should be collapsed in the Wagtail admin interface. If not provided, it defaults to False</p>
<p>Così ad esempio per questo codice. Possiamo effettuare il breakdown di questo codice in base alla regola definita:</p>
<p>`class BlogPage(Page):<br>
author = models.CharField(max_length=255, default=‘Default Author’)<br>
date = models.DateField(“Post date”)</p>
<pre><code>body = StreamField(
    [
        ('heading', blocks.CharBlock(form_classname="title")),
        ('paragraph', blocks.RichTextBlock()),
        ('image', ImageChooserBlock()),
        ('code', CodeBlock()),
        ('raw_html', RawHTMLBlock()),
    ],
    use_json_field=True
)

content_panels = Page.content_panels + [
    FieldPanel('author'),
    FieldPanel('date'),
    FieldPanel('body'),
]
</code></pre>
<p>`</p>
<p><strong>author</strong> = models.CharField(max_length=255, default=‘Default Author’): This line defines a character field named author in the BlogPage class. It has a maximum length of 255 characters and a default value of ‘Default Author’.</p>
<p><strong>date</strong> = models.DateField(“Post date”): This line defines a date field named date in the BlogPage class with a human-readable name “Post date”.</p>
<p><strong>body</strong> = StreamField([…], use_json_field=True): This line defines a stream field named body in the BlogPage class. It allows the inclusion of different block types, such as CharBlock, RichTextBlock, ImageChooserBlock, CodeBlock, and RawHTMLBlock. <strong>The use_json_field parameter is set to True, indicating that a JSON field will be used for storage.</strong></p>
<p><strong>content_panels</strong> = Page.content_panels + […]: This line defines the content panels for the Wagtail admin interface. It includes panels for ‘author’, ‘date’, and ‘body’.</p>
<p>Poi in particolare:</p>
<h4 id="content_panels-definition-in-the-blogpage-class-1">content_panels definition in the BlogPage class:####</h4>
<p><code>content_panels = Page.content_panels + [ FieldPanel('author'), FieldPanel('date'), FieldPanel('body'), ]</code></p>
<p><strong>Page.content_panels</strong>: This part includes the content panels defined in the parent Page class. It allows the inclusion of standard page fields, such as title, slug, publish date, etc.</p>
<p><strong>FieldPanel(‘author’)</strong>: This adds a panel for the author field to the content panels. It’s likely a simple text input for the author’s name.</p>
<p><strong>FieldPanel(‘date’)</strong>: This adds a panel for the date field, probably a date picker for selecting the post date.</p>
<p><strong>FieldPanel(‘body’)</strong>: This adds a panel for the body field. Since it’s a StreamField, it might include a dynamic set of blocks like headings, paragraphs, images, code blocks, and raw HTML.</p>
<h2 id="uso-dello-structbox-in-wagtail-1">Uso dello StructBox in Wagtail</h2>
<p>Example Model with StructBlock<br>
Consider a simple model for a page with a StreamField containing a StructBlock named ‘person’:</p>
<p><span>` # <a href="http://models.py">models.py</a><br>
from django.db import models<br>
from wagtail.core.fields import StreamField<br>
from wagtail.core import blocks<br>
from wagtail.images.blocks import ImageChooserBlock<br>
from wagtail.core.models import Page<br>
from wagtail.admin.edit_handlers import FieldPanel, StreamFieldPanel</span></p>
<p>class BlogPage(Page):<br>
body = StreamField([<br>
(‘person’, blocks.StructBlock([<br>
(‘first_name’, blocks.CharBlock()),<br>
(‘surname’, blocks.CharBlock()),<br>
(‘photo’, ImageChooserBlock(required=False)),<br>
(‘biography’, blocks.RichTextBlock()),<br>
])),<br>
(‘heading’, blocks.CharBlock(form_classname=“title”)),<br>
(‘paragraph’, blocks.RichTextBlock()),<br>
(‘image’, ImageChooserBlock()),<br>
], use_json_field=True)</p>
<pre><code>content_panels = Page.content_panels + [
    StreamFieldPanel('body'),
] `&lt;/span&gt;
</code></pre>
<p>Diagram Explanation<br>
Blog Page with StreamField and StructBlock:</p>
<p>A BlogPage contains a StreamField named ‘body’.<br>
‘body’ includes various block types, one of which is a StructBlock named ‘person’.<br>
Person StructBlock:</p>
<p>The ‘person’ block is a StructBlock containing fields like ‘first_name’, ‘surname’, ‘photo’, and ‘biography’.<br>
Block Instances:</p>
<p>When editing a BlogPage, you can add multiple instances of different block types, including ‘person’. Each ‘person’ block instance can have its own ‘first_name’, ‘surname’, ‘photo’, and ‘biography’</p>
<p><em><strong>Template Implementation</strong></em></p>
<p>To render this in a template, you can use the following:</p>
<pre><code>`&lt;!-- templates/blog_page.html --&gt;
{% extends "base.html" %}

{% block content %}
    &lt;article&gt;
        {% for block in page.body %}
            {% if block.block_type == 'person' %}
                &lt;div class="person"&gt;
                    {% if block.value.photo %}
                        {% image block.value.photo width-400 %}
                    {% endif %}
                    &lt;h2&gt;{{ block.value.first_name }} {{ block.value.surname }}&lt;/h2&gt;
                    {{ block.value.biography }}
                &lt;/div&gt;
            {% else %}
                {# Rendering for other block types #}
                &lt;section class="{{ block.block_type }}"&gt;
                    {% include_block block %}
                &lt;/section&gt;
            {% endif %}
        {% endfor %}
    &lt;/article&gt;
{% endblock %} 
</code></pre>
<hr>
<p><em><strong>Database Initialization</strong></em></p>
<p>When you run makemigrations and migrate after adding the StructBlock to your model, the necessary database tables and fields are created. The use_json_field=True parameter in the StreamField indicates that the data for the StreamField will be stored as JSON in the database.</p>
<p>Here’s how you perform the migration:</p>
<p>bash<br>
Copy code<br>
python <a href="http://manage.py">manage.py</a> makemigrations<br>
python <a href="http://manage.py">manage.py</a> migrate<br>
After migration, you can create or edit a BlogPage instance through the Wagtail admin interface. The StructBlock fields will be part of the form for each ‘person’ block within the ‘body’ StreamField.</p>
<h3 id="riferimenti-rapidi-wagtail-1">Riferimenti Rapidi Wagtail</h3>
<ul>
<li>
<p><a href="https://www.outreachy.org/docs/internship/">Caso Studio web page</a></p>
</li>
<li>
<p><a href="https://docs.wagtail.org/en/v5.2.1/topics/streamfield.html">How to use Streamfield for mixed content</a></p>
</li>
<li>
<p><a href="https://docs.wagtail.org/en/v5.2.1/reference/streamfield/blocks.html#streamfield-block-reference">StreamFieldBlock Reference</a></p>
</li>
</ul>
<h1 id="caratteristiche-avanzate-di-diango---wagtail-1">Caratteristiche avanzate di Diango - Wagtail</h1>
<p>Uno dei porblemi che si incontrano effettuando delle tabelle all’interno di wagtail ma in generale anche in Django è il caso pratico della renderizzazione degli headers di una tabella se si vogliono recuperare ad esempio i dati all’interno delle celle della tabella.</p>
<p><strong>Attenzione!</strong>: questo progetto è illustrato al solo fine didattico. Infatti nell’applicazione concreta vi sono notevoli problemi nell’effettuare il passaggio dei dati da Django a Wagtail. Per cui ai fini applicativi la via migliore per rendere i dati da Django a Wagtail è quella della costruzione di un API attraverso serializer (vedere capitolo)</p>
<p>Questo codice di esempio effettua il debug su ciò che è successo:</p>
<p>`<br>
<br>
{% for column in block.value.columns %}<br>
<br>
{{ column.header|default:“Column Header” }}</p>
<pre><code>            &lt;!-- Debugging statements --&gt;
            &lt;p&gt;block.value.rows: {{ block.value.rows|list }}&lt;/p&gt;
            &lt;p&gt;block.value.rows.1: {{ block.value.rows|list.1|default:"" }}&lt;/p&gt;
            
            {% with block.value.rows|list.1|default:"" as row_values %}
                {{ row_values.0|default:"" }}
            {% endwith %}
        &lt;/th&gt;
    {% endfor %}
&lt;/tr&gt;
</code></pre>

`
Un estratto di codice generato è questo 
`   <table id="datatable_1" class="display nowrap datatable">
                        <thead>
                            <tr>

</tr></thead></table><pre><code>                                &lt;th&gt;
                                    Column Header
                                    
                                    &lt;!-- Debugging statements --&gt;
                                    &lt;p&gt;block.value.rows: &amp;lt;generator object TypedTable.rows at 0x7f08958de2e0&amp;gt;&lt;/p&gt;
                                    &lt;p&gt;block.value.rows.1: &lt;/p&gt; `
</code></pre>
                    
                    <p>Approfondendo la ricerca si artriva a tale indicazione<br>
:::caution<br>
The issue seems to be related to the fact that block.value.rows is a generator object. In Python, generators are lazy and can be consumed only once. If you try to iterate through the generator more than once, you will get an empty result on subsequent iterations.</p>
<p>In your case, it seems like the generator has been consumed once, which is why when you try to access block.value.rows.1, it doesn’t contain any values.</p>
<p>To address this issue, you might want to convert the generator to a list so that you can iterate through it multiple times. However, since you are using the TypedTableBlock from wagtail.contrib.typed_table_block, you might need to adjust how you access the rows.</p>
<p>Here is a modification that converts the generator to a list before using it:</p>
<p>django<br>
Copy code</p>

    
        {% for column in block.value.columns %}
            
                {{ column.header|default:"Column Header" }}
<pre><code>            &lt;!-- Debugging statements --&gt;
            &lt;p&gt;block.value.rows: {{ block.value.rows|list }}&lt;/p&gt;
            &lt;p&gt;block.value.rows.1: {{ block.value.rows|list.1|default:"" }}&lt;/p&gt;
            
            {% with block.value.rows|list.1|default:"" as row_values %}
                {{ row_values.0|default:"" }}
            {% endwith %}
        &lt;/th&gt;
    {% endfor %}
&lt;/tr&gt;
</code></pre>

This uses the |list filter to convert the generator to a list before accessing the second row. Please note that this might not be the most efficient solution, especially if your table has a large number of rows. If efficiency is a concern, you may want to explore other ways to handle this situation.
:::
<h2 id="how-to-feed-a-table-from-django-admin-panel-open-in-as-block-into-wagtail-admin-panel-and-render-it-into-the-wagtail-frontend">HOW TO FEED A TABLE FROM DJANGO ADMIN PANEL, OPEN IN AS BLOCK INTO WAGTAIL ADMIN PANEL AND RENDER IT INTO THE WAGTAIL FRONTEND</h2>
<p>Premessa: prima di effettuare questa complessa operazione va tenuto in conto che i due progetti uno django e l’altro wagtail derivano da due repository differenti. Quindi il problema iniziale sarà quello di renedere omogenei i file .git. Per fare ciò dunque di seguito si descrive il metodo migliore individuato:</p>
<p>If you want to consolidate both the Django and Wagtail projects into a single Git repository, and you’ve already initialized separate repositories in each project’s directory, you have a couple of options:</p>
<p>Option 1: Delete Existing Git Repositories</p>
<ol>
<li>
<p><strong>Delete Git repositories in directory and subdirectories:</strong></p>
<ul>
<li>Navigate to each subdirectory (e.g., <code>django_general_template2</code> and <code>blog_wiki_wag/blog_page_wiki_wag/wiki-wag</code>) containing a Git repository.</li>
<li>Run <code>rm -rf .git</code> to delete the existing Git repository.</li>
</ul>
</li>
<li>
<p><strong>Initialize a new Git repository in the root directory:</strong></p>
<ul>
<li>Run <code>cd /path/to/django_general_template2</code> (replace <code>/path/to/django_general_template2</code> with your actual path).</li>
<li>Run <code>git init</code> to initialize a new Git repository.</li>
</ul>
</li>
<li>
<p><strong>Add, commit, and push:</strong></p>
<ul>
<li>Add all files with <code>git add .</code>.</li>
<li>Commit the changes with <code>git commit -m "Initial commit"</code>.</li>
<li>If you’ve already set up a remote repository, push the changes to it.</li>
</ul>
<p>Great! Since you’ve deleted the existing Git repositories and initialized a new one in the root directory, here are the steps to create a new GitHub repository (<code>django-wiki-wag</code>) and push your local changes to it:</p>
<ol>
<li>
<p><strong>Create a New GitHub Repository:</strong></p>
<ul>
<li>Go to <a href="https://github.com/">GitHub</a>.</li>
<li>Log in to your account.</li>
<li>Click the “+” icon in the top right corner and select “New repository.”</li>
<li>Fill in the repository name (e.g., <code>django-wiki-wag</code>), add a description if you want, and choose other repository settings.</li>
<li>Click “Create repository.”</li>
</ul>
</li>
<li>
<p><strong>Set the Remote Origin for Your Local Repository:</strong></p>
<ul>
<li>
<p>In your local terminal, navigate to the root directory of your project.</p>
</li>
<li>
<p>Run the following commands, replacing the repository URL with your newly created repository URL:</p>
<pre><code>bashCopy code
git remote add origin https://github.com/your-username/django-wiki-wag.git
</code></pre>
</li>
</ul>
</li>
<li>
<p><strong>Add, Commit, and Push:</strong></p>
<ul>
<li>
<p>Run the following commands to add all files, commit your changes, and push to GitHub:</p>
<pre><code>bashCopy codegit add .
git commit -m "Initial commit"
git push -u origin main
</code></pre>
</li>
<li>
<p>Note: Replace <code>main</code> with the name of the branch you are working on (it could be <code>master</code> or another branch).</p>
</li>
</ul>
</li>
<li>
<p><strong>Verify on GitHub:</strong></p>
<ul>
<li>Visit your GitHub repository (<code>https://github.com/your-username/django-wiki-wag</code>).</li>
<li>Confirm that your files and project structure are visible.</li>
</ul>
</li>
</ol>
<p>Now, your local project should be synchronized with the new GitHub repository. If you encounter any issues during the process, feel free to ask for further assistance!</p>
</li>
</ol>
<p>To achieve your goal, you’ll need to follow a series of steps. I’ll provide you with a step-by-step guide to make the necessary changes and additions to your Django admin, Wagtail models, and HTML template.</p>
<ul>
<li>
<p><strong>Step 1: Adjust Wagtail Settings</strong></p>
<p>In the <code>settings.py</code> of your Wagtail project (<code>wiki-wag</code>), ensure that the <code>ALLOWED_HOSTS</code> setting includes the appropriate values for your Django project. Update other settings if needed.</p>
<pre class=" language-python"><code class="prism  language-python">pythonCopy code<span class="token comment"># wiki-wag/settings/base.py</span>

ALLOWED_HOSTS <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'yourdjangoapp.com'</span><span class="token punctuation">,</span> <span class="token string">'localhost'</span><span class="token punctuation">,</span> <span class="token string">'127.0.0.1'</span><span class="token punctuation">]</span>
</code></pre>
</li>
<li>
<p><strong>Step 2: Add Wagtail settings to Django <a href="http://settings.py">settings.py</a></strong></p>
<p>In your Django project (`general_template 1), include the Wagtail settings by updating <a href="http://settings.py">settings.py</a>:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token triple-quoted-string string">"""
Django settings for general_template1 project.

Generated by 'django-admin startproject' using Django 4.2.2.

For more information on this file, see
https://docs.djangoproject.com/en/4.2/topics/settings/

For the full list of settings and their values, see
https://docs.djangoproject.com/en/4.2/ref/settings/
"""</span>

<span class="token keyword">from</span> pathlib <span class="token keyword">import</span> Path

<span class="token comment"># Build paths inside the project like this: BASE_DIR / 'subdir'.</span>
BASE_DIR <span class="token operator">=</span> Path<span class="token punctuation">(</span>__file__<span class="token punctuation">)</span><span class="token punctuation">.</span>resolve<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">.</span>parent<span class="token punctuation">.</span>parent


<span class="token comment"># Quick-start development settings - unsuitable for production</span>
<span class="token comment"># See https://docs.djangoproject.com/en/4.2/howto/deployment/checklist/</span>

<span class="token comment"># SECURITY WARNING: keep the secret key used in production secret!</span>
SECRET_KEY <span class="token operator">=</span> <span class="token string">'django-insecure-2-yc!0z!mcv#w$3vk6#s5i635l+bg#x3+24w2!26ikg4o-dj4u'</span>

<span class="token comment"># SECURITY WARNING: don't run with debug turned on in production!</span>
DEBUG <span class="token operator">=</span> <span class="token boolean">True</span>

<span class="token comment"># ALLOWED_HOSTS = ['127.0.0.1', 'localhost', '146.190.169.21'] # tiene conto delle attività su droplet</span>
ALLOWED_HOSTS <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'app.sgbh.org'</span><span class="token punctuation">,</span> <span class="token string">'www.sgbh.org'</span><span class="token punctuation">,</span> <span class="token string">'127.0.0.1'</span><span class="token punctuation">,</span> <span class="token string">'localhost'</span><span class="token punctuation">,</span> <span class="token string">'146.190.169.21'</span><span class="token punctuation">]</span>
SECURE_PROXY_SSL_HEADER <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token string">'HTTP_X_FORWARDED_PROTO'</span><span class="token punctuation">,</span> <span class="token string">'https'</span><span class="token punctuation">)</span>


<span class="token comment"># Application definition</span>

INSTALLED_APPS <span class="token operator">=</span> <span class="token punctuation">[</span>
    
    <span class="token string">'wagtail.contrib.forms'</span><span class="token punctuation">,</span>
    <span class="token string">'wagtail.contrib.redirects'</span><span class="token punctuation">,</span>
    <span class="token string">'wagtail.embeds'</span><span class="token punctuation">,</span>
    <span class="token string">'wagtail.sites'</span><span class="token punctuation">,</span>
    <span class="token string">'wagtail.users'</span><span class="token punctuation">,</span>
    <span class="token string">'wagtail.snippets'</span><span class="token punctuation">,</span>
    <span class="token string">'wagtail.documents'</span><span class="token punctuation">,</span>
    <span class="token string">'wagtail.images'</span><span class="token punctuation">,</span>
    <span class="token string">'wagtail.search'</span><span class="token punctuation">,</span>
    <span class="token string">'wagtail.admin'</span><span class="token punctuation">,</span>
    
    <span class="token string">'taggit'</span><span class="token punctuation">,</span>
    <span class="token string">'modelcluster'</span><span class="token punctuation">,</span>
  
    <span class="token string">'django.contrib.admin'</span><span class="token punctuation">,</span>
    <span class="token string">'django.contrib.auth'</span><span class="token punctuation">,</span>
    <span class="token string">'django.contrib.contenttypes'</span><span class="token punctuation">,</span>
    <span class="token string">'django.contrib.sessions'</span><span class="token punctuation">,</span>
    <span class="token string">'django.contrib.messages'</span><span class="token punctuation">,</span>
    <span class="token string">'django.contrib.staticfiles'</span><span class="token punctuation">,</span>
    <span class="token string">'sgq'</span><span class="token punctuation">,</span>
    <span class="token string">'wagtail'</span><span class="token punctuation">,</span>
<span class="token punctuation">]</span>

MIDDLEWARE <span class="token operator">=</span> <span class="token punctuation">[</span>
    <span class="token string">'django.middleware.security.SecurityMiddleware'</span><span class="token punctuation">,</span>
    <span class="token string">'django.contrib.sessions.middleware.SessionMiddleware'</span><span class="token punctuation">,</span>
    <span class="token string">'django.middleware.common.CommonMiddleware'</span><span class="token punctuation">,</span>
    <span class="token string">'django.middleware.csrf.CsrfViewMiddleware'</span><span class="token punctuation">,</span>
    <span class="token string">'django.contrib.auth.middleware.AuthenticationMiddleware'</span><span class="token punctuation">,</span>
    <span class="token string">'django.contrib.messages.middleware.MessageMiddleware'</span><span class="token punctuation">,</span>
    <span class="token string">'django.middleware.clickjacking.XFrameOptionsMiddleware'</span><span class="token punctuation">,</span>
    <span class="token string">'wagtail.contrib.redirects.middleware.RedirectMiddleware'</span><span class="token punctuation">,</span>
<span class="token punctuation">]</span>

ROOT_URLCONF <span class="token operator">=</span> <span class="token string">'general_template1.urls'</span>

TEMPLATES <span class="token operator">=</span> <span class="token punctuation">[</span>
    <span class="token punctuation">{</span>
        <span class="token string">'BACKEND'</span><span class="token punctuation">:</span> <span class="token string">'django.template.backends.django.DjangoTemplates'</span><span class="token punctuation">,</span>
        <span class="token string">'DIRS'</span><span class="token punctuation">:</span> <span class="token punctuation">[</span><span class="token punctuation">]</span><span class="token punctuation">,</span>
        <span class="token string">'APP_DIRS'</span><span class="token punctuation">:</span> <span class="token boolean">True</span><span class="token punctuation">,</span>
        <span class="token string">'OPTIONS'</span><span class="token punctuation">:</span> <span class="token punctuation">{</span>
            <span class="token string">'context_processors'</span><span class="token punctuation">:</span> <span class="token punctuation">[</span>
                <span class="token string">'django.template.context_processors.debug'</span><span class="token punctuation">,</span>
                <span class="token string">'django.template.context_processors.request'</span><span class="token punctuation">,</span>
                <span class="token string">'django.contrib.auth.context_processors.auth'</span><span class="token punctuation">,</span>
                <span class="token string">'django.contrib.messages.context_processors.messages'</span><span class="token punctuation">,</span>
            <span class="token punctuation">]</span><span class="token punctuation">,</span>
        <span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token punctuation">}</span><span class="token punctuation">,</span>
<span class="token punctuation">]</span>

WSGI_APPLICATION <span class="token operator">=</span> <span class="token string">'general_template1.wsgi.application'</span>
WSGI_SERVER_PORT <span class="token operator">=</span> <span class="token number">443</span>


<span class="token comment"># Database</span>
<span class="token comment"># https://docs.djangoproject.com/en/4.2/ref/settings/#databases</span>

DATABASES <span class="token operator">=</span> <span class="token punctuation">{</span>
    <span class="token string">'default'</span><span class="token punctuation">:</span> <span class="token punctuation">{</span>
        <span class="token string">'ENGINE'</span><span class="token punctuation">:</span> <span class="token string">'django.db.backends.sqlite3'</span><span class="token punctuation">,</span>
        <span class="token string">'NAME'</span><span class="token punctuation">:</span> BASE_DIR <span class="token operator">/</span> <span class="token string">'db.sqlite3'</span><span class="token punctuation">,</span>
    <span class="token punctuation">}</span>
<span class="token punctuation">}</span>


<span class="token comment"># Password validation</span>
<span class="token comment"># https://docs.djangoproject.com/en/4.2/ref/settings/#auth-password-validators</span>

AUTH_PASSWORD_VALIDATORS <span class="token operator">=</span> <span class="token punctuation">[</span>
    <span class="token punctuation">{</span>
        <span class="token string">'NAME'</span><span class="token punctuation">:</span> <span class="token string">'django.contrib.auth.password_validation.UserAttributeSimilarityValidator'</span><span class="token punctuation">,</span>
    <span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token punctuation">{</span>
        <span class="token string">'NAME'</span><span class="token punctuation">:</span> <span class="token string">'django.contrib.auth.password_validation.MinimumLengthValidator'</span><span class="token punctuation">,</span>
    <span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token punctuation">{</span>
        <span class="token string">'NAME'</span><span class="token punctuation">:</span> <span class="token string">'django.contrib.auth.password_validation.CommonPasswordValidator'</span><span class="token punctuation">,</span>
    <span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token punctuation">{</span>
        <span class="token string">'NAME'</span><span class="token punctuation">:</span> <span class="token string">'django.contrib.auth.password_validation.NumericPasswordValidator'</span><span class="token punctuation">,</span>
    <span class="token punctuation">}</span><span class="token punctuation">,</span>
<span class="token punctuation">]</span>


<span class="token comment"># Internationalization</span>
<span class="token comment"># https://docs.djangoproject.com/en/4.2/topics/i18n/</span>

LANGUAGE_CODE <span class="token operator">=</span> <span class="token string">'en-us'</span>

TIME_ZONE <span class="token operator">=</span> <span class="token string">'UTC'</span>

USE_I18N <span class="token operator">=</span> <span class="token boolean">True</span>

USE_TZ <span class="token operator">=</span> <span class="token boolean">True</span>


<span class="token comment"># Static files (CSS, JavaScript, Images)</span>
<span class="token comment"># https://docs.djangoproject.com/en/4.2/howto/static-files/</span>

STATIC_URL <span class="token operator">=</span> <span class="token string">'static/'</span>

<span class="token comment"># Default primary key field type</span>
<span class="token comment"># https://docs.djangoproject.com/en/4.2/ref/settings/#default-auto-field</span>

DEFAULT_AUTO_FIELD <span class="token operator">=</span> <span class="token string">'django.db.models.BigAutoField'</span>
</code></pre>
</li>
<li>
<p><strong>Step 3: Add Wagtail URLs to Django URLs</strong></p>
<p>In your Django project (`general_template 1), include the Wagtail urls by updating <a href="http://urls.py">urls.py</a>:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> django<span class="token punctuation">.</span>contrib <span class="token keyword">import</span> admin
<span class="token keyword">from</span> django<span class="token punctuation">.</span>urls <span class="token keyword">import</span> path<span class="token punctuation">,</span> include
<span class="token keyword">from</span> wagtail <span class="token keyword">import</span> urls <span class="token keyword">as</span> wagtail_urls

urlpatterns <span class="token operator">=</span> <span class="token punctuation">[</span>
    path<span class="token punctuation">(</span><span class="token string">''</span><span class="token punctuation">,</span> include<span class="token punctuation">(</span><span class="token string">'sgq.urls'</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>  <span class="token comment"># Include the app-level URLs</span>
    path<span class="token punctuation">(</span><span class="token string">'admin/'</span><span class="token punctuation">,</span> admin<span class="token punctuation">.</span>site<span class="token punctuation">.</span>urls<span class="token punctuation">)</span><span class="token punctuation">,</span>
    <span class="token comment"># path('wagtail/', include('wagtail.core.urls')), # nuovo inserimento</span>
    path<span class="token punctuation">(</span><span class="token string">'wagtail/'</span><span class="token punctuation">,</span> include<span class="token punctuation">(</span>wagtail_urls<span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span> <span class="token comment"># nuovo inserimento</span>
   
<span class="token punctuation">]</span>
</code></pre>
</li>
<li>
<p>**Step 4: Add a Fixed Table Block to Your Models **and Update BlogPage Model **<br>
In your <strong>blog/models.py</strong>, add the FixedTableBlock to the list of available blocks. This block will represent the fixed table content. Include the FixedTableBlock in the StreamField of your BlogPage model.</p>
<ul>
<li>The key changes here are adding the import for <code>FixedTableBlock</code> and including it in the <code>StreamField</code> under the name <code>'fixed_table'</code>.</li>
</ul>
</li>
</ul>
<pre class=" language-python"><code class="prism  language-python">
<span class="token keyword">from</span> wagtail<span class="token punctuation">.</span>images<span class="token punctuation">.</span>blocks <span class="token keyword">import</span> ImageChooserBlock
<span class="token keyword">from</span> wagtail<span class="token punctuation">.</span>fields <span class="token keyword">import</span> StreamField<span class="token punctuation">,</span> RichTextField
<span class="token keyword">from</span> wagtail<span class="token punctuation">.</span>admin<span class="token punctuation">.</span>panels <span class="token keyword">import</span> FieldPanel
<span class="token keyword">from</span> wagtail<span class="token punctuation">.</span>documents<span class="token punctuation">.</span>blocks <span class="token keyword">import</span> DocumentChooserBlock
<span class="token keyword">from</span> wagtail<span class="token punctuation">.</span>models <span class="token keyword">import</span> Page
<span class="token keyword">from</span> wagtail <span class="token keyword">import</span> blocks
<span class="token keyword">from</span> wagtail<span class="token punctuation">.</span>contrib<span class="token punctuation">.</span>table_block<span class="token punctuation">.</span>blocks <span class="token keyword">import</span> TableBlock
<span class="token keyword">from</span> wagtail<span class="token punctuation">.</span>contrib<span class="token punctuation">.</span>routable_page<span class="token punctuation">.</span>models <span class="token keyword">import</span> RoutablePageMixin<span class="token punctuation">,</span> path
<span class="token keyword">from</span> django<span class="token punctuation">.</span>db <span class="token keyword">import</span> models
<span class="token keyword">from</span> wagtail<span class="token punctuation">.</span>search <span class="token keyword">import</span> index
<span class="token keyword">from</span> modelcluster<span class="token punctuation">.</span>fields <span class="token keyword">import</span> ParentalKey
<span class="token keyword">from</span> wagtail<span class="token punctuation">.</span>contrib<span class="token punctuation">.</span>forms<span class="token punctuation">.</span>models <span class="token keyword">import</span> AbstractEmailForm<span class="token punctuation">,</span> AbstractFormField

<span class="token keyword">from</span> <span class="token punctuation">.</span>blocks <span class="token keyword">import</span> PublicationBlock <span class="token comment"># rif 1 - Adding in rendering get_absolute_url</span>
<span class="token keyword">from</span> wagtail<span class="token punctuation">.</span>contrib<span class="token punctuation">.</span>typed_table_block<span class="token punctuation">.</span>blocks <span class="token keyword">import</span> TypedTableBlock
<span class="token keyword">from</span> wagtail<span class="token punctuation">.</span>images<span class="token punctuation">.</span>blocks <span class="token keyword">import</span> ImageChooserBlock

<span class="token keyword">class</span> <span class="token class-name">RawHTMLBlock</span><span class="token punctuation">(</span>blocks<span class="token punctuation">.</span>RawHTMLBlock<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">class</span> <span class="token class-name">Meta</span><span class="token punctuation">:</span>
        icon <span class="token operator">=</span> <span class="token string">"code"</span>  <span class="token comment"># Set a suitable icon from available Wagtail icons</span>
        template <span class="token operator">=</span> <span class="token string">'blog/raw_html_block.html'</span>

<span class="token keyword">class</span> <span class="token class-name">CodeBlock</span><span class="token punctuation">(</span>blocks<span class="token punctuation">.</span>StructBlock<span class="token punctuation">)</span><span class="token punctuation">:</span>
    code <span class="token operator">=</span> blocks<span class="token punctuation">.</span>TextBlock<span class="token punctuation">(</span><span class="token punctuation">)</span>
    <span class="token keyword">class</span> <span class="token class-name">Meta</span><span class="token punctuation">:</span>
        template <span class="token operator">=</span> <span class="token string">'blog/code_block.html'</span>

<span class="token keyword">class</span> <span class="token class-name">FixedTableBlock</span><span class="token punctuation">(</span>blocks<span class="token punctuation">.</span>StructBlock<span class="token punctuation">)</span><span class="token punctuation">:</span>
    fixed_table_text <span class="token operator">=</span> blocks<span class="token punctuation">.</span>CharBlock<span class="token punctuation">(</span><span class="token punctuation">)</span>

    <span class="token keyword">class</span> <span class="token class-name">Meta</span><span class="token punctuation">:</span>
        icon <span class="token operator">=</span> <span class="token string">'table'</span>  <span class="token comment"># Set an icon for the block</span>
        template <span class="token operator">=</span> <span class="token string">'blog/fixed_table_block.html'</span>  <span class="token comment"># Create this template for rendering the block</span>

<span class="token keyword">class</span> <span class="token class-name">BlogPage</span><span class="token punctuation">(</span>Page<span class="token punctuation">)</span><span class="token punctuation">:</span>
    author <span class="token operator">=</span> models<span class="token punctuation">.</span>CharField<span class="token punctuation">(</span>max_length<span class="token operator">=</span><span class="token number">255</span><span class="token punctuation">,</span> default<span class="token operator">=</span><span class="token string">'Default Author'</span><span class="token punctuation">)</span>
    date <span class="token operator">=</span> models<span class="token punctuation">.</span>DateField<span class="token punctuation">(</span><span class="token string">"Post date"</span><span class="token punctuation">)</span>
    
    <span class="token comment"># New field for content choice</span>
    content_choice <span class="token operator">=</span> models<span class="token punctuation">.</span>CharField<span class="token punctuation">(</span>
        max_length<span class="token operator">=</span><span class="token number">20</span><span class="token punctuation">,</span>
        choices<span class="token operator">=</span><span class="token punctuation">[</span>
            <span class="token punctuation">(</span><span class="token string">'choice_one'</span><span class="token punctuation">,</span> <span class="token string">'Choice One'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
            <span class="token punctuation">(</span><span class="token string">'choice_two'</span><span class="token punctuation">,</span> <span class="token string">'Choice Two'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
        <span class="token punctuation">]</span><span class="token punctuation">,</span>
        default<span class="token operator">=</span><span class="token string">'choice_one'</span><span class="token punctuation">,</span>  <span class="token comment"># Set a default choice</span>
        help_text<span class="token operator">=</span><span class="token string">"Select the content to be displayed on the page."</span>
    <span class="token punctuation">)</span>
    
    body <span class="token operator">=</span> StreamField<span class="token punctuation">(</span><span class="token punctuation">[</span>
        <span class="token punctuation">(</span><span class="token string">'heading'</span><span class="token punctuation">,</span> blocks<span class="token punctuation">.</span>CharBlock<span class="token punctuation">(</span>form_classname<span class="token operator">=</span><span class="token string">"title"</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
        <span class="token punctuation">(</span><span class="token string">'paragraph'</span><span class="token punctuation">,</span> blocks<span class="token punctuation">.</span>RichTextBlock<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
        <span class="token punctuation">(</span><span class="token string">'image'</span><span class="token punctuation">,</span> ImageChooserBlock<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
        <span class="token punctuation">(</span><span class="token string">'code'</span><span class="token punctuation">,</span> CodeBlock<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
        <span class="token punctuation">(</span><span class="token string">'raw_html'</span><span class="token punctuation">,</span> RawHTMLBlock<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
        <span class="token punctuation">(</span><span class="token string">'publication'</span><span class="token punctuation">,</span> PublicationBlock<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span> <span class="token comment"># rif 1 - Adding in rendering get_absolute_url</span>
        <span class="token punctuation">(</span><span class="token string">'table'</span><span class="token punctuation">,</span> TypedTableBlock<span class="token punctuation">(</span><span class="token punctuation">[</span>
            <span class="token punctuation">(</span><span class="token string">'text'</span><span class="token punctuation">,</span> blocks<span class="token punctuation">.</span>CharBlock<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
            <span class="token punctuation">(</span><span class="token string">'numeric'</span><span class="token punctuation">,</span> blocks<span class="token punctuation">.</span>FloatBlock<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
            <span class="token punctuation">(</span><span class="token string">'rich_text'</span><span class="token punctuation">,</span> blocks<span class="token punctuation">.</span>RichTextBlock<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
            <span class="token punctuation">(</span><span class="token string">'image'</span><span class="token punctuation">,</span> ImageChooserBlock<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
            <span class="token punctuation">(</span><span class="token string">'country'</span><span class="token punctuation">,</span> blocks<span class="token punctuation">.</span>ChoiceBlock<span class="token punctuation">(</span>choices<span class="token operator">=</span><span class="token punctuation">[</span>
                <span class="token punctuation">(</span><span class="token string">'be'</span><span class="token punctuation">,</span> <span class="token string">'Belgium'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
                <span class="token punctuation">(</span><span class="token string">'fr'</span><span class="token punctuation">,</span> <span class="token string">'France'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
                <span class="token punctuation">(</span><span class="token string">'de'</span><span class="token punctuation">,</span> <span class="token string">'Germany'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
                <span class="token punctuation">(</span><span class="token string">'nl'</span><span class="token punctuation">,</span> <span class="token string">'Netherlands'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
                <span class="token punctuation">(</span><span class="token string">'pl'</span><span class="token punctuation">,</span> <span class="token string">'Poland'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
                <span class="token punctuation">(</span><span class="token string">'uk'</span><span class="token punctuation">,</span> <span class="token string">'United Kingdom'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
            <span class="token punctuation">]</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
        <span class="token punctuation">]</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
        <span class="token punctuation">(</span><span class="token string">'fixed_table'</span><span class="token punctuation">,</span> FixedTableBlock<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>  <span class="token comment"># Add the FixedTableBlock</span>
    <span class="token punctuation">]</span><span class="token punctuation">,</span> use_json_field<span class="token operator">=</span><span class="token boolean">True</span><span class="token punctuation">)</span>

    content_panels <span class="token operator">=</span> Page<span class="token punctuation">.</span>content_panels <span class="token operator">+</span> <span class="token punctuation">[</span>
        FieldPanel<span class="token punctuation">(</span><span class="token string">'author'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
        FieldPanel<span class="token punctuation">(</span><span class="token string">'date'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
        FieldPanel<span class="token punctuation">(</span><span class="token string">'content_choice'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
        FieldPanel<span class="token punctuation">(</span><span class="token string">'body'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
    <span class="token punctuation">]</span>

</code></pre>
<p>[^Removal of special-purpose field panel types]: Removal of special-purpose field panel typesThe panel types <code>StreamFieldPanel</code>, <code>RichTextFieldPanel</code>, <code>ImageChooserPanel</code>, <code>DocumentChooserPanel</code> and <code>SnippetChooserPanel</code> have been phased out, and can now be replaced with <code>FieldPanel</code>. Additionally, <code>PageChooserPanel</code> is only required when passing a <code>page_type</code> or <code>can_choose_root</code>, and can otherwise be replaced with <code>FieldPanel</code>. In all cases, <code>FieldPanel</code> will now automatically select the most appropriate form element. This feature was developed by Matt Westcott.</p>
<p>**Step 5: **Go in the <strong>Wagtail <a href="http://manage.py">manage.py</a> level</strong> and make sure to run migrations after making these changes:</p>
<pre><code>python3 manage.py makemigrations
python3 manage.py migrate
</code></pre>
<p>Now you can use the Wagtail admin to add and edit the content for the <code>fixed_table</code> block in your <code>BlogPage</code>. This content should then be rendered in your <code>blog_page.html</code></p>
<blockquote>
<p>At this stage you go into Wagtail Project via **python3 <a href="http://manage.py">manage.py</a> runserver ** into admin panel and if all works you can access and add the table. In the wagtail preview mode you receive a visualization error because the <strong>blog/fixed_table_block.html</strong> does not exists!</p>
</blockquote>
<p><strong>Step 6 - Creation of blog/fixed_table_block.html</strong></p>
<p>So before to jump to Django admin level to create an input data entry let’s try to enter the data from <strong>FixedTableBlock()</strong>. In this manner sure that all is working fine just until now.   To do this First, update the <code>FixedTableBlock</code> in <code>models.py</code>:</p>
<pre class=" language-python"><code class="prism  language-python">pythonCopy codefrom wagtail<span class="token punctuation">.</span>core <span class="token keyword">import</span> blocks

<span class="token keyword">class</span> <span class="token class-name">FixedTableBlock</span><span class="token punctuation">(</span>blocks<span class="token punctuation">.</span>StructBlock<span class="token punctuation">)</span><span class="token punctuation">:</span>
    nation <span class="token operator">=</span> blocks<span class="token punctuation">.</span>CharBlock<span class="token punctuation">(</span>required<span class="token operator">=</span><span class="token boolean">True</span><span class="token punctuation">,</span> help_text<span class="token operator">=</span><span class="token string">'Enter nation'</span><span class="token punctuation">)</span>
    capital <span class="token operator">=</span> blocks<span class="token punctuation">.</span>CharBlock<span class="token punctuation">(</span>required<span class="token operator">=</span><span class="token boolean">True</span><span class="token punctuation">,</span> help_text<span class="token operator">=</span><span class="token string">'Enter capital'</span><span class="token punctuation">)</span>

    <span class="token keyword">class</span> <span class="token class-name">Meta</span><span class="token punctuation">:</span>
        template <span class="token operator">=</span> <span class="token string">'blog/fixed_table_block.html'</span>
</code></pre>
<p>Then, create or update the template file at <strong>blog/templates/blog/fixed_table_block.html</strong>:</p>
<pre class=" language-html"><code class="prism  language-html">htmlCopy code<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>div</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>table</span> <span class="token attr-name">class</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>table table-bordered table-striped<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>thead</span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>tr</span><span class="token punctuation">&gt;</span></span>
                <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>th</span><span class="token punctuation">&gt;</span></span>Nation<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>th</span><span class="token punctuation">&gt;</span></span>
                <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>th</span><span class="token punctuation">&gt;</span></span>Capital<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>th</span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>tr</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>thead</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>tbody</span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>tr</span><span class="token punctuation">&gt;</span></span>
                <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>td</span><span class="token punctuation">&gt;</span></span>{{ value.nation }}<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>td</span><span class="token punctuation">&gt;</span></span>
                <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>td</span><span class="token punctuation">&gt;</span></span>{{ value.capital }}<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>td</span><span class="token punctuation">&gt;</span></span>
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>tr</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>tbody</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>table</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>div</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p><strong>Go in the Wagtail <a href="http://manage.py">manage.py</a> level</strong> and make sure to run migrations after making these changes:</p>
<pre class=" language-bash"><code class="prism  language-bash">python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py migrate
</code></pre>
<p>If all works you are able to input the data and see the table in Wagtail preview mode</p>
<blockquote>
<p><strong>Always remeber to conslidate you commmit pushing on Github</strong></p>
</blockquote>
<p><strong>Step 7 - Implementation <a href="http://models.py">models.py</a> - Django side</strong></p>
<p><strong>Create a Django model for the content you want to manage:</strong></p>
<p>Define a Django model in your <code>models.py</code> that represents the content you want to associate with the <code>FixedTableBlock</code></p>
<pre class=" language-python"><code class="prism  language-python">pythonCopy code<span class="token comment"># models.py</span>

<span class="token keyword">from</span> django<span class="token punctuation">.</span>db <span class="token keyword">import</span> models

<span class="token keyword">class</span> <span class="token class-name">FixedTableContent</span><span class="token punctuation">(</span>models<span class="token punctuation">.</span>Model<span class="token punctuation">)</span><span class="token punctuation">:</span>
    nation <span class="token operator">=</span> models<span class="token punctuation">.</span>CharField<span class="token punctuation">(</span>max_length<span class="token operator">=</span><span class="token number">255</span><span class="token punctuation">)</span>
    capital <span class="token operator">=</span> models<span class="token punctuation">.</span>CharField<span class="token punctuation">(</span>max_length<span class="token operator">=</span><span class="token number">255</span><span class="token punctuation">)</span>

    <span class="token keyword">def</span> <span class="token function">__str__</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">return</span> self<span class="token punctuation">.</span>nation
</code></pre>
<p><strong>Step 8 - Implementation <a href="http://admin.py">admin.py</a> - Django side</strong></p>
<p><strong>Create an admin class for the new model:</strong></p>
<p>Create an admin class for your new model in the <code>admin.py</code> file:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># admin.py</span>

<span class="token keyword">from</span> django<span class="token punctuation">.</span>contrib <span class="token keyword">import</span> admin
<span class="token keyword">from</span> <span class="token punctuation">.</span>models <span class="token keyword">import</span> FixedTableContent

@admin<span class="token punctuation">.</span>register<span class="token punctuation">(</span>FixedTableContent<span class="token punctuation">)</span>
<span class="token keyword">class</span> <span class="token class-name">FixedTableContentAdmin</span><span class="token punctuation">(</span>admin<span class="token punctuation">.</span>ModelAdmin<span class="token punctuation">)</span><span class="token punctuation">:</span>
    list_display <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token string">'nation'</span><span class="token punctuation">,</span> <span class="token string">'capital'</span><span class="token punctuation">)</span>
</code></pre>
<p>This admin class will allow you to manage instances of <code>FixedTableContent</code> in the Django admin.</p>
<p>--------- FINO A QUI –</p>
<p>template.Step 3: Create Template for FixedTableBlock<br>
Create a template file at blog/templates/blog/fixed_table_block.html for rendering the FixedTableBlock. This template will be used to display the fixed table content.</p>
<p>html<br>
Copy code<br>
<span>{{ value.fixed_table_text }}</span><br>
Step 4: Run Migrations<br>
Run the following commands to apply the model changes:</p>
<p>bash<br>
Copy code<br>
python <a href="http://manage.py">manage.py</a> makemigrations<br>
python <a href="http://manage.py">manage.py</a> migrate<br>
Step 5: Update Django Admin<br>
Create an admin class for BlogPage in blog/wagtail_hooks.py:</p>
<p>python<br>
Copy code<br>
from wagtail.contrib.modeladmin.options import (<br>
ModelAdmin, modeladmin_register, ModelAdminGroup<br>
)<br>
from .models import BlogPage</p>
<p>class BlogPageAdmin(ModelAdmin):<br>
model = BlogPage<br>
menu_label = ‘Blog Pages’<br>
menu_icon = ‘doc-full-inverse’<br>
menu_order = 200<br>
add_to_settings_menu = False<br>
exclude_from_explorer = False<br>
list_display = (‘title’, ‘author’, ‘date’, ‘content_choice’)<br>
search_fields = (‘title’, ‘author’, ‘date’, ‘content_choice’)</p>
<p>modeladmin_register(BlogPageAdmin)<br>
Step 6: Include Admin CSS<br>
In your blog/static/css/admin.css file, add the following CSS to improve the display of the custom block in the admin.</p>
<p>css<br>
Copy code<br>
.wagtail-edit-handler-fixed_table .field-content textarea {<br>
height: 100px; /* Adjust the height as needed */<br>
}<br>
Step 7: Update BlogPage Admin Panels<br>
Update the content_panels in BlogPage to include the new block:</p>
<p>python<br>
Copy code</p>
<h1 id="section">…</h1>
<p>class BlogPage(Page):<br>
# …</p>
<pre><code>content_panels = Page.content_panels + [
    FieldPanel('author'),
    FieldPanel('date'),
    FieldPanel('content_choice'),
    FieldPanel('body'),
]
</code></pre>
<p>Step 8: Update blog_page.html<br>
Update blog/templates/blog/blog_page.html to render the new FixedTableBlock.</p>
<p>html<br>
Copy code</p>
<!-- ... existing code ... -->
<p>{% for block in page.body %}<br>
{% if block.block_type == ‘fixed_table’ %}<br>
{% include_block block %}<br>
{% elif block.block_type == ‘table’ %}<br>
<!-- ... existing table code ... --><br>
{% elif block.block_type == ‘heading’ %}<br>
<!-- ... existing heading code ... --><br>
{% elif block.block_type == ‘publication’ %}<br>
<!-- ... existing publication code ... --><br>
{% else %}<br>
<!-- ... existing block code ... --><br>
{% endif %}<br>
{% endfor %}</p>
<!-- ... existing code ... -->
<p>Step 9: Restart Server<br>
Restart your development server to see the changes:</p>
<p>bash<br>
Copy code<br>
python <a href="http://manage.py">manage.py</a> runserver<br>
Now you should be able to add and edit the fixed table content in the Django admin and see it rendered on your blog_page.html. Adjust the styles and templates according to your design preferences.</p>
<p>This guide assumes a basic project structure, so adjust the paths if your project structure is different. Let me know if you have any questions or if there’s anything specific you’d like to clarify!</p>
<hr>
<h3 id="wagtail-upgrade-process-1">WAGTAIL Upgrade process</h3>
<p>We recommend upgrading one feature release at a time, even if your project is several versions behind the current one. This has a number of advantages over skipping directly to the newest release:</p>
<p>If anything breaks as a result of the upgrade, you will know which version caused it, and will be able to troubleshoot accordingly;</p>
<p>Deprecation warnings shown in the console output will notify you of any code changes you need to make before upgrading to the following version;</p>
<p>Some releases make database schema changes that need to be reflected on your project by running ./manage.py makemigrations - this is liable to fail if too many schema changes happen in one go.</p>
<p>Before upgrading to a new feature release:</p>
<p>Check your project’s console output for any deprecation warnings, and fix them where necessary;</p>
<p>Check the new version’s release notes, and the Compatible Django / Python versions table below, for any dependencies that need upgrading first;</p>
<p>Make a backup of your database.</p>
<p>To upgrade:</p>
<p>Update the wagtail line in your project’s requirements.txt file to specify the latest patch release of the version you wish to install. For example, to upgrade to version 1.8.x, the line should read:<br>
`wagtail&gt;=1.8,&lt;1.9<br>
Run:</p>
<p>pip install -r requirements.txt<br>
./manage.py makemigrations<br>
./manage.py migrate`</p>
<p>Make any necessary code changes as directed in the “Upgrade considerations” section of the release notes.</p>
<p>Test that your project is working as expected.</p>
<p>Remember that the JavaScript and CSS files used in the Wagtail admin may have changed between releases - if you encounter erratic behaviour on upgrading, ensure that you have cleared your browser cache. When deploying the upgrade to a production server, be sure to run ./manage.py collectstatic to make the updated static files available to the web server. In production, we recommend enabling ManifestStaticFilesStorage in the STATICFILES_STORAGE setting - this ensures that different versions of files are assigned distinct URLs.</p>
<h1 id="feeding-data-from-django-to-wagatail-via-api">FEEDING DATA FROM DJANGO TO WAGATAIL VIA API</h1>
<p>Steps:</p>
<p>To create a Django API app and expose the data to your Wagtail project, you can follow these steps:</p>
<h3 id="step-1-create-django-api-app-create-a-django-app-from-0">Step 1: Create Django API App (<a href="#create-a-django-app-from-0">create a Django app from 0)</a></h3>
<ol>
<li>
<p>Open your terminal and navigate to the root directory of your Django project.</p>
</li>
<li>
<p>Run the following command to create a new Django app for your API:</p>
<pre class=" language-python"><code class="prism  language-python">python manage<span class="token punctuation">.</span>py startapp django_api_for_wagtail
</code></pre>
</li>
<li>
<p>Install the Django REST framework to use it in your Django API app. Django REST framework is a powerful and flexible toolkit for building Web APIs in Django.</p>
<p>You can install it using <code>pip</code>. Open your terminal and navigate to your project’s root directory. Then, run the following command:</p>
<pre class=" language-python"><code class="prism  language-python">pip3 install djangorestframework
</code></pre>
</li>
<li>
<p>After installing, you’ll need to add <code>'rest_framework'</code> to the <code>INSTALLED_APPS</code> in your project’s <code>settings.py</code>:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># myproject/settings.py</span>
INSTALLED_APPS <span class="token operator">=</span> <span class="token punctuation">[</span>
    <span class="token comment"># ...</span>
    <span class="token string">'rest_framework'</span><span class="token punctuation">,</span>
    <span class="token comment"># ...</span>
<span class="token punctuation">]</span>
</code></pre>
<p>Now that you have a separate app named <code>django_api_for_wagtail</code> for the purpose, let’s create a data input example. Assuming you’ve created your <code>Nation</code> model within this app, here are the corrected steps:</p>
<h3 id="django-api-django-side">Django API (Django Side):</h3>
<h4 id="models.py-in-django_api_for_wagtail-app"><a href="http://models.py">models.py</a> in <code>django_api_for_wagtail</code> app:</h4>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># django_api_for_wagtail/models.py</span>
<span class="token keyword">from</span> django<span class="token punctuation">.</span>db <span class="token keyword">import</span> models

<span class="token keyword">class</span> <span class="token class-name">Nation</span><span class="token punctuation">(</span>models<span class="token punctuation">.</span>Model<span class="token punctuation">)</span><span class="token punctuation">:</span>
    name <span class="token operator">=</span> models<span class="token punctuation">.</span>CharField<span class="token punctuation">(</span>max_length<span class="token operator">=</span><span class="token number">255</span><span class="token punctuation">,</span> unique<span class="token operator">=</span><span class="token boolean">True</span><span class="token punctuation">)</span>
    capital <span class="token operator">=</span> models<span class="token punctuation">.</span>CharField<span class="token punctuation">(</span>max_length<span class="token operator">=</span><span class="token number">255</span><span class="token punctuation">)</span>

    <span class="token keyword">def</span> <span class="token function">__str__</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">return</span> self<span class="token punctuation">.</span>name
</code></pre>
<h4 id="serializers.py-in-django_api_for_wagtail-app"><a href="http://serializers.py">serializers.py</a> in <code>django_api_for_wagtail</code> app:</h4>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># django_api_for_wagtail/serializers.py</span>
<span class="token keyword">from</span> rest_framework <span class="token keyword">import</span> serializers
<span class="token keyword">from</span> <span class="token punctuation">.</span>models <span class="token keyword">import</span> Nation

<span class="token keyword">class</span> <span class="token class-name">NationSerializer</span><span class="token punctuation">(</span>serializers<span class="token punctuation">.</span>ModelSerializer<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">class</span> <span class="token class-name">Meta</span><span class="token punctuation">:</span>
        model <span class="token operator">=</span> Nation
        fields <span class="token operator">=</span> <span class="token string">'__all__'</span>
</code></pre>
<h4 id="views.py-in-django_api_for_wagtail-app"><a href="http://views.py">views.py</a> in <code>django_api_for_wagtail</code> app:</h4>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment">#django_api_for_wagtail/views.py</span>
<span class="token keyword">from</span> rest_framework <span class="token keyword">import</span> generics
<span class="token keyword">from</span> <span class="token punctuation">.</span>models <span class="token keyword">import</span> Nation
<span class="token keyword">from</span> <span class="token punctuation">.</span>serializers <span class="token keyword">import</span> NationSerializer

<span class="token keyword">class</span> <span class="token class-name">NationAPIView</span><span class="token punctuation">(</span>generics<span class="token punctuation">.</span>ListCreateAPIView<span class="token punctuation">)</span><span class="token punctuation">:</span>
    queryset <span class="token operator">=</span> Nation<span class="token punctuation">.</span>objects<span class="token punctuation">.</span><span class="token builtin">all</span><span class="token punctuation">(</span><span class="token punctuation">)</span>
    serializer_class <span class="token operator">=</span> NationSerializer
</code></pre>
<h4 id="urls.py-in-django_api_for_wagtail-app"><a href="http://urls.py">urls.py</a> in <code>django_api_for_wagtail</code> app:</h4>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># django_api_for_wagtail/urls.py</span>
<span class="token keyword">from</span> django<span class="token punctuation">.</span>urls <span class="token keyword">import</span> path
<span class="token keyword">from</span> <span class="token punctuation">.</span>views <span class="token keyword">import</span> NationAPIView

urlpatterns <span class="token operator">=</span> <span class="token punctuation">[</span>
    path<span class="token punctuation">(</span><span class="token string">'nations/'</span><span class="token punctuation">,</span> NationAPIView<span class="token punctuation">.</span>as_view<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">,</span> name<span class="token operator">=</span><span class="token string">'nation-api'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
    <span class="token comment"># Add more URL patterns as needed</span>
<span class="token punctuation">]</span>


</code></pre>
<h4 id="admin.py-in-django_api_for_wagtail-app"><a href="http://admin.py">admin.py</a> in django_api_for_wagtail app:</h4>
<p>Here’s an example of how you should register the <code>Nation</code> model in the <a href="http://admin.py">admin.py</a> file:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># django_api_for_wagtail/admin.py</span>
<span class="token keyword">from</span> django<span class="token punctuation">.</span>contrib <span class="token keyword">import</span> admin
<span class="token keyword">from</span> <span class="token punctuation">.</span>models <span class="token keyword">import</span> Nation

@admin<span class="token punctuation">.</span>register<span class="token punctuation">(</span>Nation<span class="token punctuation">)</span>
<span class="token keyword">class</span> <span class="token class-name">NationAdmin</span><span class="token punctuation">(</span>admin<span class="token punctuation">.</span>ModelAdmin<span class="token punctuation">)</span><span class="token punctuation">:</span>
    list_display <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token string">'name'</span><span class="token punctuation">,</span> <span class="token string">'capital'</span><span class="token punctuation">)</span>
</code></pre>
<h4 id="urls.py-in-progetto_api-project"><a href="http://urls.py">urls.py</a> in progetto_api project:</h4>
<p>To make Django recognize the URLs of your <code>django_api_for_wagtail</code> app, you need to include the URLs of your app in the <code>urls.py</code> file at the project level. You can do this using Django’s <code>include()</code> function, which allows you to reference other URL configurations.</p>
<p>Here’s how you might update your <code>urls.py</code> file at the project level:Python</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> django<span class="token punctuation">.</span>contrib <span class="token keyword">import</span> admin
<span class="token keyword">from</span> django<span class="token punctuation">.</span>urls <span class="token keyword">import</span> include<span class="token punctuation">,</span> path

urlpatterns <span class="token operator">=</span> <span class="token punctuation">[</span>
    path<span class="token punctuation">(</span><span class="token string">"admin/"</span><span class="token punctuation">,</span> admin<span class="token punctuation">.</span>site<span class="token punctuation">.</span>urls<span class="token punctuation">)</span><span class="token punctuation">,</span>
    path<span class="token punctuation">(</span><span class="token string">"django_api_for_wagtail/"</span><span class="token punctuation">,</span> include<span class="token punctuation">(</span><span class="token string">'django_api_for_wagtail.urls'</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
<span class="token punctuation">]</span>
</code></pre>
</li>
</ol>
<h3 id="test-if-the-steps-are-correct">Test if the steps are correct</h3>
<pre class=" language-python"><code class="prism  language-python">python3 manage<span class="token punctuation">.</span>py makemigrations
</code></pre>
<pre class=" language-python"><code class="prism  language-python">python3 manage<span class="token punctuation">.</span>py migrate
</code></pre>
<p>If all is ok you can try:</p>
<p><a href="http://127.0.0.1:8000/django_api_for_wagtail/nations/">http://127.0.0.1:8000/django_api_for_wagtail/nations/</a> (frontend side - with json results)</p>
<p><a href="http://127.0.0.1:8000/admin/django_api_for_wagtail/nation/">http://127.0.0.1:8000/admin/django_api_for_wagtail/nation/</a> (backend side - with admin panel)</p>
<p>In this way, I can verify the correct data entry on the backend side and the correct management in JSON on the frontend side.</p>
<h3 id="step-2-create-views-for-api">Step 2: Create Views for API</h3>
<ol>
<li>
<p>In the <code>api</code> app directory, create a <code>views.py</code> file.</p>
</li>
<li>
<p>Define a view for your API in <code>views.py</code>. For example:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> rest_framework <span class="token keyword">import</span> generics
<span class="token keyword">from</span> blog<span class="token punctuation">.</span>models <span class="token keyword">import</span> BlogPage
<span class="token keyword">from</span> <span class="token punctuation">.</span>serializers <span class="token keyword">import</span> BlogPageSerializer

<span class="token keyword">class</span> <span class="token class-name">BlogPageAPIView</span><span class="token punctuation">(</span>generics<span class="token punctuation">.</span>ListAPIView<span class="token punctuation">)</span><span class="token punctuation">:</span>
    queryset <span class="token operator">=</span> BlogPage<span class="token punctuation">.</span>objects<span class="token punctuation">.</span><span class="token builtin">all</span><span class="token punctuation">(</span><span class="token punctuation">)</span>
    serializer_class <span class="token operator">=</span> BlogPageSerializer
</code></pre>
</li>
</ol>
<h3 id="step-3-configure-urls-for-api">Step 3: Configure URLs for API</h3>
<ol>
<li>
<p>In the <code>api</code> app directory, create a <code>urls.py</code> file.</p>
</li>
<li>
<p>Define the URL patterns for your API in <code>urls.py</code>. For example:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> django<span class="token punctuation">.</span>urls <span class="token keyword">import</span> path
<span class="token keyword">from</span> <span class="token punctuation">.</span>views <span class="token keyword">import</span> BlogPageAPIView

urlpatterns <span class="token operator">=</span> <span class="token punctuation">[</span>
    path<span class="token punctuation">(</span><span class="token string">'blog/'</span><span class="token punctuation">,</span> BlogPageAPIView<span class="token punctuation">.</span>as_view<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">,</span> name<span class="token operator">=</span><span class="token string">'blog-api'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
    <span class="token comment"># Add more URL patterns as needed</span>
<span class="token punctuation">]</span>
</code></pre>
</li>
</ol>
<h3 id="step-4-configure-main-project-urls">Step 4: Configure Main Project URLs</h3>
<ol>
<li>
<p>In the main project directory, open the <code>urls.py</code> file.</p>
</li>
<li>
<p>Include the URLs of your API app in the project’s URL configuration. Update the <code>urlpatterns</code>:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> django<span class="token punctuation">.</span>contrib <span class="token keyword">import</span> admin
<span class="token keyword">from</span> django<span class="token punctuation">.</span>urls <span class="token keyword">import</span> path<span class="token punctuation">,</span> include

urlpatterns <span class="token operator">=</span> <span class="token punctuation">[</span>
    path<span class="token punctuation">(</span><span class="token string">'admin/'</span><span class="token punctuation">,</span> admin<span class="token punctuation">.</span>site<span class="token punctuation">.</span>urls<span class="token punctuation">)</span><span class="token punctuation">,</span>
    path<span class="token punctuation">(</span><span class="token string">'api/'</span><span class="token punctuation">,</span> include<span class="token punctuation">(</span><span class="token string">'api.urls'</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>  <span class="token comment"># Adjust the URL pattern as needed</span>
    <span class="token comment"># Add other URL patterns as needed</span>
<span class="token punctuation">]</span>
</code></pre>
</li>
</ol>
<h3 id="step-5-run-migrations-and-start-the-development-server">Step 5: Run Migrations and Start the Development Server</h3>
<ol>
<li>
<p>Run the following commands to apply migrations and start the development server:</p>
<pre class=" language-bash"><code class="prism  language-bash">manage.py makemigrations
python manage.py migrate
python manage.py runserver
</code></pre>
</li>
</ol>
<h2 id="definitive-code-for-mini-django-project-api">Definitive Code for mini Django project API</h2>
<h3 id="step-6-create-the-a-frontend-to-see-the-data-">Step 6: create the a frontend (to see the data )</h3>
<p>To create a simple frontend to visualize the results from your Django API, you can use Django’s built-in templates. Here’s a step-by-step guide:</p>
<ol>
<li>
<p>Create a <code>templates</code> directory within your <code>django_api_for_wagtail</code> app.</p>
</li>
<li>
<p>Inside the <code>templates</code> directory, create an HTML file for rendering the nation data. Let’s call it <code>nations_list.html</code>.</p>
<pre class=" language-html"><code class="prism  language-html"><span class="token comment">&lt;!-- django_api_for_wagtail/templates/nations_list.html --&gt;</span>
<span class="token doctype">&lt;!DOCTYPE html&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>html</span> <span class="token attr-name">lang</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>en<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>head</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>meta</span> <span class="token attr-name">charset</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>UTF-8<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>meta</span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>viewport<span class="token punctuation">"</span></span> <span class="token attr-name">content</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>width=device-width, initial-scale=1.0<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>title</span><span class="token punctuation">&gt;</span></span>Nations List<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>title</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>head</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>body</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h1</span><span class="token punctuation">&gt;</span></span>Nations List<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h1</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>ul</span><span class="token punctuation">&gt;</span></span>
        {% for nation in nations %}
            <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>li</span><span class="token punctuation">&gt;</span></span>{{ nation.name }} - {{ nation.capital }}<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>li</span><span class="token punctuation">&gt;</span></span>
        {% endfor %}
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>ul</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>body</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>html</span><span class="token punctuation">&gt;</span></span>
</code></pre>
</li>
<li>
<p>Update your <code>views.py</code> to use this template:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># django_api_for_wagtail/views.py</span>
<span class="token keyword">from</span> django<span class="token punctuation">.</span>shortcuts <span class="token keyword">import</span> render
<span class="token keyword">from</span> rest_framework <span class="token keyword">import</span> generics
<span class="token keyword">from</span> <span class="token punctuation">.</span>models <span class="token keyword">import</span> Nation
<span class="token keyword">from</span> <span class="token punctuation">.</span>serializers <span class="token keyword">import</span> NationSerializer

<span class="token keyword">class</span> <span class="token class-name">NationAPIView</span><span class="token punctuation">(</span>generics<span class="token punctuation">.</span>ListCreateAPIView<span class="token punctuation">)</span><span class="token punctuation">:</span>
    queryset <span class="token operator">=</span> Nation<span class="token punctuation">.</span>objects<span class="token punctuation">.</span><span class="token builtin">all</span><span class="token punctuation">(</span><span class="token punctuation">)</span>
    serializer_class <span class="token operator">=</span> NationSerializer

    <span class="token keyword">def</span> <span class="token function">list</span><span class="token punctuation">(</span>self<span class="token punctuation">,</span> request<span class="token punctuation">,</span> <span class="token operator">*</span>args<span class="token punctuation">,</span> <span class="token operator">**</span>kwargs<span class="token punctuation">)</span><span class="token punctuation">:</span>
        nations <span class="token operator">=</span> self<span class="token punctuation">.</span>get_queryset<span class="token punctuation">(</span><span class="token punctuation">)</span>
        <span class="token keyword">return</span> render<span class="token punctuation">(</span>request<span class="token punctuation">,</span> <span class="token string">'nations_list.html'</span><span class="token punctuation">,</span> <span class="token punctuation">{</span><span class="token string">'nations'</span><span class="token punctuation">:</span> nations<span class="token punctuation">}</span><span class="token punctuation">)</span>
</code></pre>
<p>It is worth to breakdown the code above:</p>
<p>Let’s break down the <code>list</code> method in the <code>NationAPIView</code> class:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># django_api_for_wagtail/views.py</span>

<span class="token keyword">from</span> django<span class="token punctuation">.</span>shortcuts <span class="token keyword">import</span> render
<span class="token keyword">from</span> rest_framework <span class="token keyword">import</span> generics
<span class="token keyword">from</span> <span class="token punctuation">.</span>models <span class="token keyword">import</span> Nation
<span class="token keyword">from</span> <span class="token punctuation">.</span>serializers <span class="token keyword">import</span> NationSerializer

<span class="token keyword">class</span> <span class="token class-name">NationAPIView</span><span class="token punctuation">(</span>generics<span class="token punctuation">.</span>ListCreateAPIView<span class="token punctuation">)</span><span class="token punctuation">:</span>
    queryset <span class="token operator">=</span> Nation<span class="token punctuation">.</span>objects<span class="token punctuation">.</span><span class="token builtin">all</span><span class="token punctuation">(</span><span class="token punctuation">)</span>
    serializer_class <span class="token operator">=</span> NationSerializer

    <span class="token keyword">def</span> <span class="token function">list</span><span class="token punctuation">(</span>self<span class="token punctuation">,</span> request<span class="token punctuation">,</span> <span class="token operator">*</span>args<span class="token punctuation">,</span> <span class="token operator">**</span>kwargs<span class="token punctuation">)</span><span class="token punctuation">:</span>
        nations <span class="token operator">=</span> self<span class="token punctuation">.</span>get_queryset<span class="token punctuation">(</span><span class="token punctuation">)</span>
        <span class="token keyword">return</span> render<span class="token punctuation">(</span>request<span class="token punctuation">,</span> <span class="token string">'nations_list.html'</span><span class="token punctuation">,</span> <span class="token punctuation">{</span><span class="token string">'nations'</span><span class="token punctuation">:</span> nations<span class="token punctuation">}</span><span class="token punctuation">)</span>
</code></pre>
<ol>
<li><strong><code>queryset</code> and <code>serializer_class</code></strong>: These are attributes of the <code>NationAPIView</code> class. <code>queryset</code> defines the initial query set of nations, and <code>serializer_class</code> specifies the serializer to be used for serializing the data.</li>
<li><strong><code>list</code> method</strong>: This method is part of the <code>ListCreateAPIView</code> class provided by Django REST Framework. It handles the HTTP GET request for the list view.</li>
<li><strong><code>self.get_queryset()</code></strong>: This method retrieves the query set of nations. In this case, it gets all the objects from the <code>Nation</code> model specified in the <code>queryset</code> attribute.</li>
<li><strong><code>render</code> function</strong>: This function is used to render an HTML template. It takes the following parameters:
<ul>
<li><code>request</code>: The HTTP request object.</li>
<li><code>'nations_list.html'</code>: The name of the template file to be rendered.</li>
<li><code>{'nations': nations}</code>: A dictionary containing data to be passed to the template. In this case, it includes the retrieved nations from the query set.</li>
</ul>
</li>
<li><strong><code>return render(...)</code></strong>: This line returns the rendered HTML content as an HTTP response. The rendered content will be the result of applying the data from the <code>nations</code> query set to the ‘nations_list.html’ template.</li>
</ol>
<p>In summary, when a user accesses the URL associated with the <code>NationAPIView</code>, the <code>list</code> method is called. It retrieves the list of nations, passes them to the ‘nations_list.html’ template, renders the HTML content, and returns it as an HTTP response. This allows you to view a list of nations in a web browser when accessing the corresponding URL.</p>
<p>Let’s break down the <code>list</code> method in more detail:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token builtin">list</span><span class="token punctuation">(</span>self<span class="token punctuation">,</span> request<span class="token punctuation">,</span> <span class="token operator">*</span>args<span class="token punctuation">,</span> <span class="token operator">**</span>kwargs<span class="token punctuation">)</span><span class="token punctuation">:</span>
    nations <span class="token operator">=</span> self<span class="token punctuation">.</span>get_queryset<span class="token punctuation">(</span><span class="token punctuation">)</span>
    <span class="token keyword">return</span> render<span class="token punctuation">(</span>request<span class="token punctuation">,</span> <span class="token string">'nations_list.html'</span><span class="token punctuation">,</span> <span class="token punctuation">{</span><span class="token string">'nations'</span><span class="token punctuation">:</span> nations<span class="token punctuation">}</span><span class="token punctuation">)</span>
</code></pre>
<ol>
<li>
<p><strong><code>self</code></strong>: In Python, <code>self</code> is a convention for referring to the instance of the class. In this context, it represents an instance of the <code>NationAPIView</code> class.</p>
</li>
<li>
<p><strong><code>request</code></strong>: This is the HTTP request object that is passed to the view. It contains information about the incoming request, such as the method (GET, POST, etc.), headers, and any data sent in the request.</p>
</li>
<li>
<p><strong><code>\*args</code> and <code>\**kwargs</code></strong>: These are used to collect additional positional and keyword arguments. In this case, they are not used in the method body, but the method signature includes them to allow flexibility.The usage of <code>*args</code> and <code>**kwargs</code> provides flexibility when defining functions or methods that can accept a variable number of arguments.</p>
<h6 id="using-args-for-variable-positional-arguments"><strong>Using <code>\*args</code> for Variable Positional Arguments:</strong></h6>
<pre class=" language-python"><code class="prism  language-python">example_function<span class="token punctuation">(</span><span class="token operator">*</span>args<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">for</span> arg <span class="token keyword">in</span> args<span class="token punctuation">:</span>
        <span class="token keyword">print</span><span class="token punctuation">(</span>arg<span class="token punctuation">)</span>

example_function<span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">,</span> <span class="token string">'four'</span><span class="token punctuation">)</span>
</code></pre>
<p>In this example, <code>*args</code> allows the function to accept any number of positional arguments. It collects them into a tuple named <code>args</code>, and the function can iterate over them.</p>
<ol>
<li>
<p><strong>Using <code>\**kwargs</code> for Variable Keyword Arguments:</strong></p>
<pre class=" language-python"><code class="prism  language-python">example_function<span class="token punctuation">(</span><span class="token operator">**</span>kwargs<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">for</span> key<span class="token punctuation">,</span> value <span class="token keyword">in</span> kwargs<span class="token punctuation">.</span>items<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">print</span><span class="token punctuation">(</span>f<span class="token string">"{key}: {value}"</span><span class="token punctuation">)</span>

example_function<span class="token punctuation">(</span>name<span class="token operator">=</span><span class="token string">'John'</span><span class="token punctuation">,</span> age<span class="token operator">=</span><span class="token number">25</span><span class="token punctuation">,</span> city<span class="token operator">=</span><span class="token string">'New York'</span><span class="token punctuation">)</span>
</code></pre>
<p>In this example, <code>**kwargs</code> allows the function to accept any number of keyword arguments. It collects them into a dictionary named <code>kwargs</code>, and the function can iterate over the key-value pairs.</p>
</li>
<li>
<p><strong>Combining <code>\*args</code> and <code>\**kwargs</code>:</strong></p>
<pre><code>example_function(arg1, arg2, *args, **kwargs):
    print(f"arg1: {arg1}")
    print(f"arg2: {arg2}")
    print(f"Additional positional arguments: {args}")
    print(f"Additional keyword arguments: {kwargs}")

example_function(1, 2, 3, 4, key1='value1', key2='value2')
</code></pre>
<p>In this example, <code>arg1</code> and <code>arg2</code> are regular positional arguments, <code>*args</code> collects additional positional arguments into a tuple, and <code>**kwargs</code> collects additional keyword arguments into a dictionary.</p>
</li>
</ol>
<p>Using <code>*args</code> and <code>**kwargs</code> allows a function or method to be more flexible and accommodate a varying number of arguments without explicitly specifying them in the function signature. This is particularly useful in cases where the number of arguments might change or when writing functions that need to work with a wide range of inputs.</p>
</li>
<li>
<p><strong><code>self.get_queryset()</code></strong>: This method is inherited from the <code>ListCreateAPIView</code> class of Django REST Framework. It retrieves the queryset of nations. The <code>get_queryset</code> method is responsible for returning the list of objects that will be used in the view.</p>
</li>
<li>
<p><strong><code>nations</code></strong>: This variable stores the queryset of nations obtained from <code>self.get_queryset()</code>.</p>
</li>
<li>
<p><strong><code>render(request, 'nations_list.html', {'nations': nations})</code></strong>: The <code>render</code> function is a shortcut provided by Django for rendering an HTML template. It takes the following arguments:</p>
<ul>
<li><code>request</code>: The HTTP request object.</li>
</ul>
</li>
</ol>
<ul>
<li><code>'nations_list.html'</code>: The name of the HTML template file to be rendered.
<ul>
<li><code>{'nations': nations}</code>: A dictionary containing data to be passed to the template. In this case, it includes the list of nations obtained from the queryset.</li>
</ul>
</li>
</ul>
<ol start="8">
<li><strong><code>return render(...)</code></strong>: This line returns the rendered HTML content as an HTTP response. The rendered content will be the result of applying the data from the <code>nations</code> queryset to the ‘nations_list.html’ template.</li>
</ol>
<p>In summary, the <code>list</code> method is responsible for retrieving a queryset of nations and rendering an HTML template (‘nations_list.html’) with the nations’ data. The rendered HTML content is then returned as an HTTP response. This is a common pattern for providing a list view in a Django REST Framework API.</p>
</li>
<li>
<h4 id="update-your-urls.py-to-include-a-url-pattern-for-rendering-the-nations-list">Update your <code>urls.py</code> to include a URL pattern for rendering the nations list:</h4>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># django_api_for_wagtail/urls.py</span>
<span class="token keyword">from</span> django<span class="token punctuation">.</span>urls <span class="token keyword">import</span> path
<span class="token keyword">from</span> <span class="token punctuation">.</span>views <span class="token keyword">import</span> NationAPIView

urlpatterns <span class="token operator">=</span> <span class="token punctuation">[</span>
    path<span class="token punctuation">(</span><span class="token string">'nations/'</span><span class="token punctuation">,</span> NationAPIView<span class="token punctuation">.</span>as_view<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">,</span> name<span class="token operator">=</span><span class="token string">'nation-api'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
    path<span class="token punctuation">(</span><span class="token string">'nations/list/'</span><span class="token punctuation">,</span> NationAPIView<span class="token punctuation">.</span>as_view<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">,</span> name<span class="token operator">=</span><span class="token string">'nations-list'</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
    <span class="token comment"># Add more URL patterns as needed</span>
<span class="token punctuation">]</span>
</code></pre>
</li>
<li>
<p>Finally, update your <code>urls.py</code> at the project level to include the <code>django_api_for_wagtail</code> URLs:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># progetto_api/urls.py</span>
<span class="token keyword">from</span> django<span class="token punctuation">.</span>contrib <span class="token keyword">import</span> admin
<span class="token keyword">from</span> django<span class="token punctuation">.</span>urls <span class="token keyword">import</span> path<span class="token punctuation">,</span> include

urlpatterns <span class="token operator">=</span> <span class="token punctuation">[</span>
    path<span class="token punctuation">(</span><span class="token string">'admin/'</span><span class="token punctuation">,</span> admin<span class="token punctuation">.</span>site<span class="token punctuation">.</span>urls<span class="token punctuation">)</span><span class="token punctuation">,</span>
    path<span class="token punctuation">(</span><span class="token string">'django_api_for_wagtail/'</span><span class="token punctuation">,</span> include<span class="token punctuation">(</span><span class="token string">'django_api_for_wagtail.urls'</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span>
<span class="token punctuation">]</span>
</code></pre>
</li>
</ol>
<p>Now, when you visit the URL <a href="http://127.0.0.1:8000/django_api_for_wagtail/nations/list/">http://127.0.0.1:8000/django_api_for_wagtail/nations/list/</a>, it should render the nations list using the template.</p>
<hr>
<p>Fino a qui</p>
<h3 id="step-6-access-the-api">Step 6: Access the API</h3>
<ol>
<li>Open your web browser and navigate to <code>http://127.0.0.1:8000/api/blog/</code> (or the URL you configured).</li>
<li>You should see the serialized data from your Wagtail model.</li>
</ol>
<h3 id="step-7-integrate-with-wagtail">Step 7: Integrate with Wagtail</h3>
<ol>
<li>In your Wagtail project, you can now fetch data from the API endpoint (<code>http://127.0.0.1:8000/api/blog/</code>) using Django’s <code>requests</code> library or any other method you prefer.</li>
<li>Use the retrieved data to populate your Wagtail views/templates as needed.</li>
</ol>
<p>This is a basic setup, and you may need to customize it based on your specific requirements. Additionally, you might want to add authentication and permission controls to secure your API.</p>
<h3 id="wagtail-compatibility-with-django----link">WAGTAIL COMPATIBILITY WITH DJANGO ## - <a href="https://docs.wagtail.org/en/latest/releases/upgrading.html">link</a></h3>
<h1 id="python-1">PYTHON</h1>
<h2 id="spiegazione-attraverso-codice-di-init-getattribute-e-super-1">Spiegazione attraverso codice di <strong>init</strong>, <strong>getattribute</strong> e super</h2>
<p>Spesso nei moduli di wagtail si fa riferimento alla classazione e subclassazione. Avere chiri alcuni termini è necessario. Questa è la breve sintesi attraverso un sempio</p>
<p><code>class Vehicle: def</code><strong>init</strong>(self, brand):<br>
self.brand = brand</p>
<pre><code>def start(self):
    print(f"{self.brand} vehicle started.")`
</code></pre>
<p>This is a simple class representing a vehicle with a brand.<br>
It has an <strong>init</strong> method that initializes the brand attribute and a start method to print a message when the vehicle starts.<br>
Car (inherits from Vehicle):</p>
<p>python<br>
Copy code<br>
class Car(Vehicle):<br>
def <strong>init</strong>(self, brand, model):<br>
# No use of super()<br>
self.model = model</p>
<pre><code>def start(self):
    print(f"{self.brand} {self.model} car started.")
</code></pre>
<p>This class represents a specific type of vehicle, a Car, inheriting from the Vehicle class.<br>
It has its own <strong>init</strong> method, but it doesn’t use super(), and it has a start method that overrides the start method in the Vehicle class.<br>
CarWithSuper (inherits from Car):</p>
<p>class CarWithSuper(Car):<br>
def <strong>init</strong>(self, brand, model, color):<br>
super().<strong>init</strong>(brand, model)<br>
self.color = color</p>
<pre><code>def start(self):
    super().start()
    print(f"The {self.color} car is ready to go.")

def __getattribute__(self, name):
    # Modifying __getattribute__ to add a prefix to the brand attribute
    if name == "brand":
        return "Awesome " + super().__getattribute__(name)
    else:
        return super().__getattribute__(name)
</code></pre>
<p>This class inherits from Car and introduces a new attribute color.<br>
It uses super() in the <strong>init</strong> method to call the <strong>init</strong> method of the parent class (Car).<br>
It overrides the start method, calls the parent’s start method using super(), and adds an additional message.<br>
It also modifies <strong>getattribute</strong> to add a prefix (“Awesome”) to the brand attribute.<br>
Examples:<br>
Example without super(), <strong>init</strong>, and <strong>getattribute</strong>:</p>
<p><code>car_without_super = Car(brand="Toyota", model="Camry") print(car_without_super.model) # Output: Camry An instance of Car is created without using super(). __init__ in Car is called, but __init__ of the parent (Vehicle) is not called. start method from Vehicle is not available in car_without_super. Example with super(), __init__, and __getattribute__: car_with_super = CarWithSuper(brand="Ford", model="Mustang", color="red") print(car_with_super.brand) # Output: Awesome Ford car_with_super.start() # Output: Ford Mustang car started. The red car is ready to go.</code></p>
<p>An instance of CarWithSuper is created using super() to call <strong>init</strong> of the parent (Car).<br>
<strong>getattribute</strong> is modified to add a prefix to the brand attribute.<br>
start method calls the parent’s (Car) start method using super() and adds an additional message.<br>
Roles:</p>
<p><em><strong><strong>init</strong>:</strong></em><br>
Used for initializing the attributes of an object.<br>
In the inheritance chain, it’s common to use super().<strong>init</strong>(…) to call the initializer of the parent class.</p>
<p><em><strong><strong>getattribute</strong>:</strong></em> Called whenever an attribute of an object is accessed.<br>
Can be modified to customize attribute access.<br>
Used here to modify the behavior of accessing the brand attribute.</p>
<p><em><strong>super():</strong></em> Used to refer to the parent class.<br>
In <strong>init</strong>, it’s used to call the initializer of the parent class.<br>
In methods, it’s used to call methods from the parent class.<br>
In the provided example, super() helps maintain the hierarchy in inheritance, ensuring that the methods of the parent classes are appropriately called. <strong>init</strong> is used for object initialization, and <strong>getattribute</strong> is modified to customize attribute access.</p>
<h3 id="vediamo-ora-cosa-succede-se-non-utilizziamo-i-metodi-1">Vediamo ora cosa succede se non utilizziamo i metodi</h3>
<h3 id="assenza-di-init-1">Assenza di <strong>init</strong></h3>
<p>If you don’t use the <strong>init</strong> method in the Vehicle class, the class will still be valid, but instances of the class won’t have a constructor to initialize their state. The <strong>init</strong> method is a special method in Python classes that is automatically called when an object is created. It is used for initializing the attributes of the object.</p>
<p>Here’s what happens when you don’t include <strong>init</strong>:</p>
<p>python<br>
Copy code<br>
class Vehicle:<br>
def start(self):<br>
print(“Vehicle started.”)</p>
<h2 id="creating-an-instance-without-init-1">Creating an instance without <strong>init</strong></h2>
<p>vehicle_instance = Vehicle()</p>
<h2 id="this-will-not-raise-an-error-but-the-instance-wont-have-a-brand-attribute.-1">This will not raise an error, but the instance won’t have a ‘brand’ attribute.</h2>
<h3 id="if-you-try-to-access-brand-it-will-result-in-an-attributeerror.-1">If you try to access ‘brand’, it will result in an AttributeError.</h3>
<p>print(vehicle_instance.start())  # Output: Vehicle started.<br>
print(vehicle_instance.brand)  # AttributeError: ‘Vehicle’ object has no attribute ‘brand’<br>
In the example above, creating an instance of Vehicle without an <strong>init</strong> method is allowed. However, without an <strong>init</strong> method, instances won’t have any attributes initialized during instantiation. If you try to access an attribute that hasn’t been defined, you will get an AttributeError.</p>
<p>Including the <strong>init</strong> method allows you to initialize the state of an object when it is created. For example:</p>
<p>python<br>
Copy code<br>
class Vehicle:<br>
def <strong>init</strong>(self, brand):<br>
self.brand = brand</p>
<pre><code>def start(self):
    print(f"{self.brand} vehicle started.")
</code></pre>
<h1 id="creating-an-instance-with-init-1">Creating an instance with <strong>init</strong></h1>
<p>vehicle_instance = Vehicle(brand=“Toyota”)</p>
<h1 id="now-the-brand-attribute-is-initialized-during-instantiation.">Now, the ‘brand’ attribute is initialized during instantiation.</h1>
<p>print(vehicle_instance.start())  # Output: Toyota vehicle started.<br>
print(vehicle_instance.brand)  # Output: Toyota<br>
In the second example, the <strong>init</strong> method is used to initialize the brand attribute when a Vehicle instance is created. This ensures that the instance has a properly initialized state from the beginning.</p>
<h4 id="ed-ora-quando-posso-usare-e-non-usare-getattribute-1">Ed ora quando posso usare e non usare <strong>getattribute</strong>?###</h4>
<p>If you don’t define the <strong>getattribute</strong> method in a class, Python will use the default behavior for attribute access. The default behavior involves looking up the attribute in the object’s dictionary and returning its value if found. If the attribute is not found in the object’s dictionary, Python looks for the attribute in the class hierarchy.</p>
<p>Here’s what happens if you don’t use <strong>getattribute</strong>:</p>
<p>python<br>
Copy code<br>
class Vehicle:<br>
def <strong>init</strong>(self, brand):<br>
self.brand = brand</p>
<pre><code>def start(self):
    print(f"{self.brand} vehicle started.")
</code></pre>
<h2 id="creating-an-instance-without-getattribute-1">Creating an instance without <strong>getattribute</strong></h2>
<p>vehicle_instance = Vehicle(brand=“Toyota”)</p>
<h2 id="accessing-the-brand-attribute-without-a-custom-getattribute-1">Accessing the ‘brand’ attribute without a custom <strong>getattribute</strong></h2>
<p>print(vehicle_instance.brand)  # Output: Toyota</p>
<h3 id="the-default-behavior-is-used-and-there-is-no-need-for-a-custom-getattribute-in-this-case.-1">The default behavior is used, and there is no need for a custom <strong>getattribute</strong> in this case.</h3>
<p>In the example above, we create a Vehicle class with an <strong>init</strong> method to initialize the brand attribute. When we access the brand attribute, the default attribute access behavior is used, and there is no need for a custom <strong>getattribute</strong>. The attribute is found in the instance’s dictionary, and its value is returned.</p>
<p>The <strong>getattribute</strong> method is a powerful tool for customizing attribute access, and it allows you to intercept attribute access calls and customize the behavior. However, in many cases, you may not need to override it, and the default behavior is sufficient for basic attribute access. Only when you need to customize the attribute access behavior should you consider defining a <strong>getattribute</strong> method.</p>
<p>In the example provided, the <strong>getattribute</strong> method is used to customize the behavior of accessing the brand attribute in the CarWithSuper class. Specifically, it adds a prefix (“Awesome”) to the value of the brand attribute before returning it.</p>
<p>Here’s the relevant part of the code:</p>
<p>python<br>
Copy code<br>
class CarWithSuper(Car):<br>
# …</p>
<pre><code>def __getattribute__(self, name):
    # Modifying __getattribute__ to add a prefix to the brand attribute
    if name == "brand":
        return "Awesome " + super().__getattribute__(name)
    else:
        return super().__getattribute__(name)
</code></pre>
<p>In this case, the <strong>getattribute</strong> method is modifying the behavior of accessing the brand attribute. Without this customization, accessing car_with_super.brand would simply return the value of the brand attribute. With the custom <strong>getattribute</strong>, it returns the value with the added prefix.</p>
<p>So, you might need to use <strong>getattribute</strong> when you want to customize or intercept attribute access calls and modify the behavior based on your specific requirements. It’s a powerful tool, but it should be used judiciously, as unnecessary or incorrect use may lead to unexpected behavior and potential issues.</p>
<h2 id="mixin-1">MIXIN</h2>
<p>L’esempio esposto e che di seguito si ripropone risulta anche un ottimo esempio di mixin</p>
<p>Yes, the provided example with Vehicle, Car, and CarWithSuper can be considered an example of mixin-like behavior. Let me break it down:</p>
<p>Vehicle Class:</p>
<p>python<br>
Copy code<br>
class Vehicle:<br>
def <strong>init</strong>(self, brand):<br>
self.brand = brand</p>
<pre><code>def start(self):
    print(f"{self.brand} vehicle started.")
</code></pre>
<p>This is the base class representing a generic vehicle. It has an <strong>init</strong> method to initialize the brand attribute and a start method.</p>
<p>Car Class (Inherits from Vehicle):</p>
<p>python<br>
Copy code<br>
class Car(Vehicle):<br>
def <strong>init</strong>(self, brand, model):<br>
super().<strong>init</strong>(brand)<br>
self.model = model</p>
<pre><code>def start(self):
    print(f"{self.brand} {self.model} car started.")
</code></pre>
<p>The Car class inherits from Vehicle. It has its own <strong>init</strong> method but uses super() to call the <strong>init</strong> method of the parent class (Vehicle). It also has its own start method, overriding the start method of Vehicle.</p>
<p>CarWithSuper Class (Inherits from Car):</p>
<p>python<br>
Copy code<br>
class CarWithSuper(Car):<br>
def <strong>init</strong>(self, brand, model, color):<br>
super().<strong>init</strong>(brand, model)<br>
self.color = color</p>
<pre><code>def start(self):
    super().start()
    print(f"The {self.color} car is ready to go.")

def __getattribute__(self, name):
    if name == "brand":
        return "Awesome " + super().__getattribute__('brand')
    else:
        return super().__getattribute__(name)
</code></pre>
<p>The CarWithSuper class inherits from Car and introduces a new attribute (color). It uses super() to call the <strong>init</strong> method of the parent class (Car). It also overrides the start method, calling the parent’s (Car) start method using super() and adding an additional message. Additionally, it modifies <strong>getattribute</strong> to add a prefix (“Awesome”) to the brand attribute.</p>
<p>So, in this example, the classes are organized in a way that exhibits mixin-like behavior. The CarWithSuper class enhances the behavior of the Car class by adding attributes and modifying methods, and it uses super() to maintain the hierarchy and call methods from parent classes. While it may not strictly adhere to the classic definition of a mixin, it shares some characteristics of mixin-like behavior.</p>
<h3 id="definizione-di-mixin-1">Definizione di mixin</h3>
<p>In object-oriented programming, a mixin is a class that provides a certain functionality to be inherited by a subclass, but is not meant to stand alone. Mixins are used to enhance the functionality of a class without the need for multiple inheritance.</p>
<p>Here are some key characteristics and features of mixins:</p>
<p>Purpose-Specific Functionality: Mixins are designed to provide a specific set of functionalities or behaviors that can be easily added to other classes. They encapsulate a piece of behavior.</p>
<p>Reusability: Mixins promote code reuse. Instead of duplicating code in multiple classes, you can create a mixin and include it in various classes that need that particular behavior.</p>
<p>No Standalone Use: Mixins are not meant to be instantiated or used independently. They lack the complete implementation to be used as standalone classes. They are intended to be combined with other classes.</p>
<p>Flexible Composition: Since a class can inherit from multiple mixins, it allows for flexible composition of functionalities. This is in contrast to languages that do not support multiple inheritance directly.</p>
<p>Avoids Diamond Problem: Mixins can help avoid the “diamond problem” that arises in languages with multiple inheritance, where a class inherits from two classes that have a common ancestor.</p>
<p>Small and Focused: Mixins are typically small and focused on a specific task. This makes them easy to understand, maintain, and reuse.</p>
<h1 id="standard-commands-in-django-installation-1">STANDARD COMMANDS IN DJANGO INSTALLATION#</h1>
<ol>
<li>python3 -m venv venv</li>
</ol>
<h1 id="useful-property-and-method-in-django-1">USEFUL PROPERTY AND METHOD IN DJANGO</h1>
<h2 id="luso-di-queryset-1">L’uso di Queryset</h2>
<p>Django querysets have several notable properties and methods that provide flexibility and ease of use when interacting with the database. Here are some key properties and methods of querysets:</p>
<p>Chaining:</p>
<p>Querysets are lazy, meaning they don’t hit the database until an action is performed.<br>
Multiple filters and operations can be chained together to build complex queries.<br>
Example:</p>
<p>python<br>
Copy code<br>
queryset = Model.objects.filter(field1=value1).exclude(field2=value2).order_by(’-date_created’)<br>
Slicing:</p>
<p>Querysets can be sliced to retrieve a specific range of objects.<br>
Example:</p>
<p>python<br>
Copy code<br>
queryset = Model.objects.all()<br>
result_slice = queryset[5:10]  # Retrieve objects 5 through 9<br>
Count:</p>
<p>The count method returns the number of objects in the queryset without fetching the actual objects.<br>
Example:</p>
<p>python<br>
Copy code<br>
count = queryset.count()<br>
Distinct:</p>
<p>The distinct method eliminates duplicate rows from the queryset.<br>
Example:</p>
<p>python<br>
Copy code<br>
distinct_values = Model.objects.values(‘field’).distinct()<br>
Aggregate:</p>
<p>The aggregate method allows for the calculation of aggregate values (e.g., sum, average) on the queryset.<br>
Example:</p>
<p>python<br>
Copy code<br>
from django.db.models import Avg<br>
average_value = Model.objects.aggregate(avg_value=Avg(‘numeric_field’))<br>
Values and ValuesList:</p>
<p>The values method returns a queryset of dictionaries representing the values of specific fields.<br>
The values_list method returns a queryset of tuples representing the values of specific fields.<br>
Example:</p>
<p>python<br>
Copy code<br>
values_queryset = Model.objects.values(‘field1’, ‘field2’)<br>
values_list_queryset = Model.objects.values_list(‘field1’, ‘field2’)<br>
Exists:</p>
<p>The exists method checks if there are any records in the queryset.<br>
Example:</p>
<p>queryset_exists = Model.objects.filter(field=value).exists()<br>
Update and Delete:</p>
<p>The update method modifies multiple records in the database without fetching them.<br>
The delete method deletes records from the database without fetching them.<br>
Example:</p>
<p>python<br>
Copy code<br>
Model.objects.filter(field=value).update(status=‘new_status’)<br>
Model.objects.filter(field=value).delete()<br>
These are just a few of the many properties and methods provided by Django querysets. They offer a powerful and expressive way to interact with the database.</p>
<h3 id="esempio-in-wagtail-1">Esempio in wagtail</h3>
<p>from datetime import datetime, timedelta, timezone<br>
from django.shortcuts import render<br>
from wagtail.core.models import Page<br>
from your_app.models import RoundPage  # Replace ‘your_app’ with the actual name of your app<br>
from path.to.get_deadline_date_for import get_deadline_date_for  # Replace ‘<a href="http://path.to">path.to</a>’ with the actual path</p>
<p>def docs_internship(request):<br>
now = datetime.now(timezone.utc)<br>
today = get_deadline_date_for(now)<br>
five_weeks_ago = today - timedelta(days=7 * 5)</p>
<pre><code>applicant_round = RoundPage.objects.filter(
    pingnew__lte=today,
    internannounce__gt=today,
).first()

intern_round = RoundPage.objects.filter(
    internannounce__lte=today,
    internends__gt=five_weeks_ago,
).first()

return render(request, 'home/docs/internship_guide.html', {
    'applicant_round': applicant_round,
    'intern_round': intern_round,
})
</code></pre>
<h2 id="strumenti-avanzati-creare-una-pagina-wagtail-allinterno-di-un-sito-django"># Strumenti avanzati: Creare una pagina wagtail all’interno di un sito Django</h2>
<ul>
<li>
<p>(link)[<a href="https://docs.wagtail.org/en/latest/advanced_topics/add_to_django_project.html">https://docs.wagtail.org/en/latest/advanced_topics/add_to_django_project.html</a>]</p>
</li>
<li>
<p>Installazione in Django al pari livello di <a href="http://manage.py">manage.py</a>: <code>python3 manage.py startapp blog_wiki_wag</code></p>
</li>
<li>
<p>Verifica in Wagtail di requirements.txt della compatibilità delle versioni tra Django e Wagtail. Nel caso specifico Django&gt;=4.2,&lt;4.3 - wagtail&gt;=5.1,&lt;5.2</p>
</li>
<li>
<p>Verifica in Django di requirements.txt: Django==4.2.2</p>
</li>
<li>
<p>Se vi è compatibilità in Wagtal: <code>pip3 freeze requriments.txt</code></p>
</li>
<li>
<p>*** Verifica del motore Database in Wagtail in <a href="http://base.py">base.py</a>: ***</p>
</li>
<li>
<p><code>DATABASES = { "default": { "ENGINE": "django.db.backends.sqlite3", "NAME": os.path.join(BASE_DIR, "db.sqlite3"), } }</code></p>
</li>
<li>
<p>*** Verifica del motore database in Django in <a href="http://settings.py">settings.py</a>: ***</p>
</li>
<li>
<p><code>DATABASES = { 'default': { 'ENGINE': 'django.db.backends.sqlite3', 'NAME': BASE_DIR / 'db.sqlite3', } }</code></p>
</li>
<li>
<p>Come si può vedere sopra i due motori DB sono identici</p>
</li>
<li>
<p>Ora creare la subdirectory di progetto wagtail che conterrà tutti i file dell’app wagtail (quella con il quale si effettuato il requirements.txt)</p>
</li>
<li>
<p>effettuare il clone del branch da GB del progetto wagtail (vedere git e github per i dettagli)</p>
</li>
<li>
<p>a questo punto lanciare il comando Install the Project:</p>
</li>
</ul>
<p>Navigate to the wagtail-wag directory in your terminal: <code>pip install -r requirements.txt</code></p>
<ul>
<li>
<p>Add Wagtail URLs to Django URLs: <code>path('wagtail/', include('wiki-wag.wagtail_urls')), # nuovo inserimento</code></p>
</li>
<li>
<p>Add the required wagtail modules in <a href="http://setting.py">setting.py</a>: `INSTALLED_APPS = [</p>
<p>‘wagtail.contrib.forms’,<br>
‘wagtail.contrib.redirects’,<br>
‘wagtail.embeds’,<br>
‘wagtail.sites’,<br>
‘wagtail.users’,<br>
‘wagtail.snippets’,<br>
‘wagtail.documents’,<br>
‘wagtail.images’,<br>
‘wagtail.search’,<br>
‘wagtail.admin’,</p>
<p>‘taggit’,<br>
‘modelcluster’,</p>
<p>‘django.contrib.admin’,<br>
‘django.contrib.auth’,<br>
‘django.contrib.contenttypes’,<br>
‘django.contrib.sessions’,<br>
‘django.contrib.messages’,<br>
‘django.contrib.staticfiles’,<br>
‘sgq’,<br>
‘wagtail’,<br>
]`</p>
</li>
<li>
<p>Add’wiki-wag’ app in your Django INSTALLED_APPS as well. Add it if it’s not present.</p>
</li>
</ul>
<p>INSTALLED_APPS = [<br>
# …<br>
‘wiki-wag’,<br>
# …<br>
]</p>
<ul>
<li>
<p>add in Django settings this:<br>
` MIDDLEWARE = [<br>
‘django.contrib.sessions.middleware.SessionMiddleware’,<br>
‘django.middleware.common.CommonMiddleware’,<br>
‘django.middleware.csrf.CsrfViewMiddleware’,<br>
‘django.contrib.auth.middleware.AuthenticationMiddleware’,<br>
‘django.contrib.messages.middleware.MessageMiddleware’,<br>
‘django.middleware.clickjacking.XFrameOptionsMiddleware’,<br>
‘django.middleware.security.SecurityMiddleware’,</p>
<p>‘wagtail.contrib.redirects.middleware.RedirectMiddleware’,<br>
] `</p>
</li>
</ul>
<p>A questo punto dvrebbe apparire un Warning che indica qualcosa di questo genere<br>
:::caution<br>
WARNINGS:<br>
?: (wagtailadmin.W003) The WAGTAILADMIN_BASE_URL setting is not defined<br>
HINT: This should be the base URL used to access the Wagtail admin site. Without this, URLs in notification emails will not display correctly<br>
:::</p>
<p>Proseguire e verificare se in admin panel appaiono gli elementi di inpunt in Admin Panel</p>
<h2 id="so-now-update-the-urls-and-run-makemirgations-and-migrate">So now update the urls and run makemirgations and migrate</h2>
<p>from django.contrib import admin<br>
from django.urls import path, include<br>
from wagtail import urls as wagtail_urls</p>
<p>urlpatterns = [<br>
path(’’, include(‘sgq.urls’)),  # Include the app-level URLs<br>
path(‘admin/’, admin.site.urls),<br>
# path(‘wagtail/’, include(‘wagtail.core.urls’)), # nuovo inserimento<br>
path(‘wagtail/’, include(wagtail_urls)), # nuovo inserimento</p>
<p>]</p>
<h1 id="django">DJANGO</h1>
<h2 id="create-a-django-app-from-0-from-create-django-api-app-">Create a Django App from 0 (from <a href="#create-django-api-app">Create Django API App</a> )</h2>
<h3 id="step-1-create-a-virtual-environment-optional-but-recommended">Step 1: Create a Virtual Environment (Optional but recommended)</h3>
<p>Open your terminal and navigate to the directory where you want to create your Django project. Run the following commands:</p>
<pre class=" language-python"><code class="prism  language-python">python3 <span class="token operator">-</span>m venv venv
source venv<span class="token operator">/</span><span class="token builtin">bin</span><span class="token operator">/</span>activate
</code></pre>
<h3 id="step-2-install-django">Step 2: Install Django</h3>
<p>While in the activated virtual environment, install Django using the following command:</p>
<pre class=" language-python"><code class="prism  language-python">pip3 install django
</code></pre>
<p>Step 3: Create a Django Project</p>
<p>Run the following command to create a new Django project:</p>
<pre class=" language-python"><code class="prism  language-python">django<span class="token operator">-</span>admin startproject progetto_api
</code></pre>
<p>Replace <code>myproject</code> with the desired name for your project.</p>
<h3 id="step-4-navigate-to-the-project-directory">Step 4: Navigate to the Project Directory</h3>
<p>Change into the project directory:</p>
<pre class=" language-python"><code class="prism  language-python">cd progetto_api
</code></pre>
<h3 id="step-5-create-a-django-app">Step 5: Create a Django App</h3>
<p>Run the following command to create a new Django app:</p>
<pre class=" language-python"><code class="prism  language-python">python3 manage<span class="token punctuation">.</span>py startapp django_api_for_wagtail
</code></pre>
<h3 id="step-6-configure-database">Step 6: Configure Database</h3>
<p>Open the <code>myproject/settings.py</code> file and configure the app and the database settings. By default, Django uses SQLite for development (if not already configured):</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token comment"># myproject/settings.py</span>
INSTALLED_APPS <span class="token operator">=</span> <span class="token punctuation">[</span>
    <span class="token comment"># ...</span>
    <span class="token string">'django_api_for_wagtail'</span><span class="token punctuation">,</span>
    <span class="token comment"># ...</span>
<span class="token punctuation">]</span>

<span class="token comment"># .... #</span>


DATABASES <span class="token operator">=</span> <span class="token punctuation">{</span>
    <span class="token string">'default'</span><span class="token punctuation">:</span> <span class="token punctuation">{</span>
        <span class="token string">'ENGINE'</span><span class="token punctuation">:</span> <span class="token string">'django.db.backends.sqlite3'</span><span class="token punctuation">,</span>
        <span class="token string">'NAME'</span><span class="token punctuation">:</span> BASE_DIR <span class="token operator">/</span> <span class="token string">"db.sqlite3"</span><span class="token punctuation">,</span>
    <span class="token punctuation">}</span>
<span class="token punctuation">}</span>
</code></pre>
<h3 id="step-7-apply-migrations">Step 7: Apply Migrations</h3>
<p>Run the following commands to apply initial migrations:</p>
<pre class=" language-python"><code class="prism  language-python">python3 manage<span class="token punctuation">.</span>py makemigrations
python3 manage<span class="token punctuation">.</span>py migrate
</code></pre>
<h3 id="step-8-create-a-superuser-optional-but-recommended">Step 8: Create a Superuser (Optional but recommended)</h3>
<p>Run the following command to create a superuser account for the Django admin:</p>
<pre><code>bashCopy code
python manage.py createsuperuser
</code></pre>
<p>Follow the prompts to set a username, email, and password.</p>
<h3 id="step-9-run-the-development-server">Step 9: Run the Development Server</h3>
<p>Start the Django development server:</p>
<pre class=" language-python3"><code class="prism  language-python3">python3 manage.py runserver
</code></pre>
<p>Visit <code>http://127.0.0.1:8000/</code> in your web browser to see the Django welcome page.</p>
<h3 id="step-10-create-a-superuser">Step 10: Create a Superuser</h3>
<ol>
<li>
<p>After running the development server return e to your project directory (at <a href="http://manage.py">manage.py</a> level).</p>
</li>
<li>
<p>Run the following command to create a superuser account:</p>
<pre class=" language-python"><code class="prism  language-python">python3 manage<span class="token punctuation">.</span>py createsuperuser
</code></pre>
</li>
<li>
<p>Follow the prompts to set a username, email, and password for the superuser account.</p>
</li>
</ol>
<h3 id="step-11-run-the-development-server">Step 11: Run the Development Server</h3>
<p>Ensure that the development server is still running:</p>
<pre class=" language-python"><code class="prism  language-python">python3 manage<span class="token punctuation">.</span>py runserver
</code></pre>
<h3 id="step-12-open-the-admin-interface">Step 12: Open the Admin Interface</h3>
<p>Visit <code>http://127.0.0.1:8000/admin/</code> in your web browser. Log in with the superuser credentials you just created.</p>
<h3 id="step-13-verify-admin-interface">Step 13: Verify Admin Interface</h3>
<p>Verify that the Django admin interface is working correctly</p>
<h3 id="step-14-initialize-a-git-repository">Step 14: Initialize a Git Repository</h3>
<ol>
<li>
<p>Open a new terminal window in your project directory</p>
</li>
<li>
<p>The Git commands to initialize a repository, add files, and make an initial commit should be executed at the root level of your project, where your <code>manage.py</code> file is located. The <code>manage.py</code> file is typically located at the top level of your Django project, not within the virtual environment (<code>venv</code>).</p>
</li>
<li>
<p>Run the following commands to initialize a Git repository, add all files, and make an initial commit:</p>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token function">git</span> init
<span class="token function">git</span> add <span class="token keyword">.</span>
<span class="token function">git</span> commit -m <span class="token string">"Initial commit"</span>
</code></pre>
</li>
</ol>
<h3 id="step-15-create-a-github-repository">Step 15: Create a GitHub Repository</h3>
<ol>
<li>Go to the <a href="https://github.com/">GitHub website</a> and log in or create a new account.</li>
<li>Click on the “+” icon in the top right corner and select “New repository.”</li>
<li>Follow the instructions to create a new repository on GitHub.</li>
<li>git repo name <a href="https://github.com/progettazionemauro/django-api">https://github.com/progettazionemauro/django-api</a></li>
</ol>
<h3 id="step-16-connect-local-repository-to-github">Step 16: Connect Local Repository to GitHub</h3>
<ol>
<li>
<p>After creating the GitHub repository follow those instructions.</p>
<ul>
<li>
<p><code>git remote add origin https://github.com/progettazionemauro/django-api</code></p>
</li>
<li>
<p>git branch -M main</p>
<p>note: The <code>git branch -M main</code> command is used to rename the current branch. In Git, it’s a way to both rename the current branch and force-update the tracking branches.</p>
<p>Here’s what the command does:</p>
<ul>
<li><code>git branch</code>: This command is used for creating, listing, renaming, and deleting branches in Git. When used without additional options, it lists all the local branches.</li>
<li><code>-M main</code>: This option is used to rename the current branch to “main”. The <code>-M</code> flag is a shortcut for <code>--move</code>, which is used for renaming branches.</li>
</ul>
<p>When you create a new Git repository or clone an existing one, the default branch is usually named “master.” However, in recent years, there has been a movement in the Git community to use more inclusive and neutral terminology. As a result, many projects are now using “main” instead of “master” as the default branch name.</p>
<p>The <code>git branch -M main</code> command is often used after creating a new repository or when transitioning from “master” to “main” to update the branch name.</p>
<p>It’s important to note that if you’re renaming the branch you are currently on, you might need to update the remote repository to reflect the new branch name.</p>
</li>
</ul>
<pre><code>git remote add origin https://github.com/progettazionemauro/django-api
git branch -M main
git push -u origin main
</code></pre>
<p>Make sure to replace “your-username” and “your-repo” with your GitHub username and repository name.</p>
<h2 id="step-16-bis-problems-with-git-push">Step 16 bis: problems with git push</h2>
<p>In doing push it can happen to find issues related to pushing for the first time into Github. For example when you created the repo and added <a href="http://readme.md">readme.md</a> and it is not present into local repo this can generate a misealignment that che lead to generate an error likse that:</p>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token function">git</span> push origin main
<span class="token variable"><span class="token variable">`</span>To https://github.com/progettazionemauro/django-api<span class="token variable">`</span></span>
 <span class="token variable"><span class="token variable">`</span><span class="token operator">!</span> <span class="token punctuation">[</span>rejected<span class="token punctuation">]</span>        main -<span class="token operator">&gt;</span> main <span class="token punctuation">(</span>non-fast-forward<span class="token punctuation">)</span><span class="token variable">`</span></span>
`error: push di alcuni riferimenti <span class="token function">su</span> <span class="token string">'https://github.com/progettazionemauro/django-api'</span> non riuscito<span class="token variable"><span class="token variable">`</span>
<span class="token variable">`</span></span>suggerimento: Gli aggiornamenti sono stati rifiutati perché l<span class="token string">'ultimo commit del branch<span class="token variable"><span class="token variable">`</span>
<span class="token variable">`</span></span>suggerimento: attuale è rimasto indietro rispetto alla sua controparte remota.<span class="token variable"><span class="token variable">`</span>
<span class="token variable">`</span></span>suggerimento: Integra le modifiche remote (ad es. con '</span><span class="token function">git</span> pull <span class="token punctuation">..</span>.<span class="token string">') prima di<span class="token variable"><span class="token variable">`</span>
<span class="token variable">`</span></span>suggerimento: eseguire nuovamente il push.<span class="token variable"><span class="token variable">`</span>
<span class="token variable">`</span></span>suggerimento: Vedi la '</span>Nota sui fast forward<span class="token string">' in '</span><span class="token function">git</span> push --help' per ulteriori<span class="token variable"><span class="token variable">`</span>
<span class="token variable">`</span></span>suggerimento: dettagli.`
</code></pre>
<p>So it this is the case the best option if to do this:</p>
<p>In alternativa, puoi anche eseguire il comando:<code>git push --force</code> per forzare il push delle tue modifiche, anche se non sono un fast forward. Tuttavia, questa è una soluzione rischiosa perché potrebbe sovrascrivere le modifiche remote che non hai ancora integrato nel tuo branch locale.</p>
<p>Per capire meglio cosa significa “non-fast-forward”, è necessario comprendere il concetto di fast forward. Un fast forward è un tipo di push che aggiorna un branch locale con le ultime modifiche apportate a un branch remoto. Il fast forward è possibile solo se le modifiche apportate ai due branch sono consecutive.</p>
</li>
</ol>
<h3 id="step-16-verify-github-repository">Step 16: Verify GitHub Repository</h3>
<p>Go to your GitHub repository in the web browser and verify that your code has been pushed successfully.</p>
<p>That’s it! Now you have a Django project with a superuser account, and your code is version-controlled using Git and hosted on GitHub.</p>
<h3 id="step-10-create-models-views-and-templates-optional">Step 10: Create Models, Views, and Templates (Optional)</h3>
<p>You can now start building your Django app by creating models, views, and templates. Define your models in the <code>models.py</code> file, create views in the <code>views.py</code> file, and add templates in the <code>templates</code> directory.</p>
<h3 id="step-11-create-api-app-optional">Step 11: Create API App (Optional)</h3>
<p>If you want to create a separate app for your API, follow the instructions provided in the previous response to create an <code>api</code> app and set up serializers, views, and URLs.</p>
<p>That’s it! You now have a basic Django project and app set up. Customize it based on your specific requirements and integrate it with your Wagtail project as needed.</p>
<h1 id="advanced-bash-commands--django">ADVANCED BASH COMMANDS &amp; DJANGO</h1>
<h2 id="comando-per-generare-pagine-in-hugo">Comando per generare pagine in Hugo</h2>
<p>#!/bin/bash</p>
<pre><code># Define paths

posts_dir="../sgb_start/content/posts"

template_file="./../cheatsheet.md"  # Adjust this path to the location of your cheatsheet.md file

  

# Check if the posts directory exists

if [ !  -d  "$posts_dir" ]; then

echo  "Error: Hugo posts directory not found!"

exit  1

fi

  

# Check if the template file exists

if [ !  -f  "$template_file" ]; then

echo  "Error: Template file not found!"

exit  1

fi

  

# Define the new file name

new_post_file="$posts_dir/il_mio_secondo_post.md"

  

# Check if the new post file already exists

if [ -f  "$new_post_file" ]; then

echo  "Error: il_mio_secondo_post.md already exists!"

exit  1

fi

  

# Extract front matter using sed

front_matter=$(sed  -n '/^\+\+\+/,/^\+\+\+/p' "$posts_dir/il_mio_primo_post.md")

  

# Check if front matter is empty

if [ -z  "$front_matter" ]; then

echo  "Error: Front matter not found in il_mio_primo_post.md"

exit  1

fi

  

# Append the front matter to the new post file

echo  "$front_matter"  &gt;  "$new_post_file"

  

# Append the content of the template file to the new post file

cat  "$template_file"  &gt;&gt;  "$new_post_file"

  

echo  "New post created successfully: $new_post_file"
</code></pre>
<h3 id="implementazione-del-comando-add_sheet.sh-into-django-nella-medesima-app">Implementazione del comando add_sheet.sh into Django (nella medesima app)</h3>
<h3 id="django-app-admin.py">Django app: <a href="http://admin.py">admin.py</a></h3>
<pre><code>from  django.contrib  import  admin

from .models  import  Nation, CustomFeature

import  os

import  subprocess

  

@admin.register(Nation)

class  NationAdmin(admin.ModelAdmin):

list_display  = ('name', 'capital')

  

@admin.register(CustomFeature)

class  CustomFeatureAdmin(admin.ModelAdmin):

list_display  = ('name', 'description')

  

def  run_script(self, request, queryset):

try:

# This line retrieves the directory path of the current Python script (admin.py in this case) using __file__,

# which is a special attribute in Python that represents the current file path.
### Django app: admin.py
    current_dir  =  os.path.dirname(__file__)
    
    script_path  =  os.path.abspath(os.path.join(current_dir, 'add_page.sh'))
    
    print("Absolute path to script:", script_path) # Print out the absolute path
    
    subprocess.run([script_path], check=True)
    
    self.message_user(request, "Script executed successfully")
    
    except  Exception  as  e:
    
    self.message_user(request, f"Script execution failed: {e}", level='ERROR')
    
      
      
    
    run_script.short_description =  "Run add_page.sh"
    
      
    
    actions  = [run_script]
</code></pre>
<h3 id="django-app-models.py">Django app: <a href="http://models.py">models.py</a></h3>
<pre><code>from  django.db  import  models

  

class  Nation(models.Model):

name  =  models.CharField(max_length=255, unique=True)

capital  =  models.CharField(max_length=255)

  

def  __str__(self):

return  self.name

  

class  CustomFeature(models.Model):

name  =  models.CharField(max_length=255, unique=True)

description  =  models.TextField()

  

def  __str__(self):

return  self.name
</code></pre>
<h3 id="addendum-for-test-path.py">Addendum for test: <a href="http://path.py">path.py</a></h3>
<pre><code>import  os

  

def  run_script1():

# Get the directory containing the current script file

current_dir  =  os.path.dirname(__file__)

# Construct the full path to the script

script_path  =  os.path.abspath(os.path.join(current_dir, '..', '..', 'progetto_api', 'add_page.sh'))

return  script_path

  

def  runs_script2():

current_dir  =  os.path.dirname(__file__)

script_path2  =  os.path.abspath(os.path.join(current_dir, 'add_page.sh'))

return  script_path2

  

# Print the output directly in the terminal

print(run_script1())

print(runs_script2())
</code></pre>

    </div>
  </div>
</body>

</html>
