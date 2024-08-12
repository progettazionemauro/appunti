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
<li><a href="#welcome-to-stackedit">Welcome to StackEdit!</a></li>
<li><a href="#files">Files</a>
<ul>
<li><a href="#create-files-and-folders">Create files and folders</a></li>
<li><a href="#switch-to-another-file">Switch to another file</a></li>
<li><a href="#rename-a-file">Rename a file</a></li>
<li><a href="#delete-a-file">Delete a file</a></li>
<li><a href="#export-a-file">Export a file</a></li>
</ul>
</li>
<li><a href="#synchronization">Synchronization</a>
<ul>
<li><a href="#open-a-file">Open a file</a></li>
<li><a href="#save-a-file">Save a file</a></li>
<li><a href="#synchronize-a-file">Synchronize a file</a></li>
<li><a href="#manage-file-synchronization">Manage file synchronization</a></li>
</ul>
</li>
<li><a href="#publication">Publication</a>
<ul>
<li><a href="#publish-a-file">Publish a File</a></li>
<li><a href="#update-a-publication">Update a publication</a></li>
<li><a href="#manage-file-publication">Manage file publication</a></li>
</ul>
</li>
<li><a href="#markdown-extensions">Markdown extensions</a>
<ul>
<li><a href="#smartypants">SmartyPants</a></li>
<li><a href="#katex">KaTeX</a></li>
<li><a href="#uml-diagrams">UML diagrams</a></li>
</ul>
</li>
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
<li><a href="#the-subprocess-module-wrapping-programs-with-python">THE subprocess Module: Wrapping Programs With Python</a></li>
<li><a href="#overview-of-the-python--subprocess--module">Overview of the Python  subprocess  Module</a></li>
<li><a href="#basic-usage-of-the-python--subprocess--module">Basic Usage of the Python  subprocess  Module</a></li>
<li><a href="#basic-usage-of-the-python--subprocess">Basic Usage of the Python  subprocess</a></li>
<li><a href="#subprocess--exceptions">subprocess  Exceptions</a></li>
<li><a href="#introduction-to-the-shell-and-text-based-programs-with--subprocess">Introduction to the Shell and Text-Based Programs With  subprocess</a></li>
<li><a href="#communication-with-processes">Communication With Processes</a></li>
<li><a href="#pipes-and-the-shell">Pipes and the Shell</a></li>
<li><a href="#practical-ideas">Practical Ideas</a></li>
<li><a href="#python-modules-associated-with--subprocess">Python Modules Associated With  subprocess</a></li>
<li><a href="#the--popen--class">The  Popen  Class</a></li>
<li><a href="#conclusion">Conclusion</a>
<ul>
<li></li>
</ul>
</li>
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
<li><a href="#section-1">…</a>
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
<li><a href="#from-django-to-hugo---mauro-project---djungo">FROM DJANGO TO HUGO - Mauro Project - DJUNGO</a></li>
<li><a href="#integrazione-esterna---creare-un-post-da-django-a-hugo">Integrazione Esterna - Creare un POST da Django a Hugo</a>
<ul>
<li><a href="#creazione-di-post">Creazione di Post:</a></li>
<li><a href="#cancellazione-di-post">Cancellazione di Post:</a></li>
<li><a href="#aggiornamento-di-post">Aggiornamento di Post:</a></li>
<li><a href="#integrazione-dei-link-delle-immagini">Integrazione dei Link delle Immagini:</a></li>
</ul>
</li>
<li><a href="#integrazione-interna---aggiornare-un-database-da-django-a-hugo">Integrazione Interna - Aggiornare un database da Django a Hugo</a>
<ul>
<li><a href="#step-by-step-guide-to-integrate-django-api-with-hugo">Step-by-Step Guide to Integrate Django API with Hugo</a></li>
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
<li><a href="#working-with-django-app">Working with Django APP</a></li>
</ul>
</li>
<li><a href="#directory-containing-markdown-files">Directory containing markdown files</a></li>
<li><a href="#output-file-to-store-processed-file-details">Output file to store processed file details</a></li>
<li><a href="#check-if-the-directory-exists">Check if the directory exists</a></li>
<li><a href="#create-or-clear-the-output-file">Create or clear the output file</a></li>
<li><a href="#iterate-over-all-markdown-files-in-the-directory">Iterate over all markdown files in the directory</a></li>
<li><a href="#read-contents-of-the-markdown-file-and-escape-problematic-characters">Read contents of the markdown file and escape problematic characters</a></li>
<li><a href="#extract-title-from-filename">Extract title from filename</a></li>
<li><a href="#construct-image_link-based-on-the-extracted-title">Construct image_link based on the extracted title</a></li>
<li><a href="#print-the-details-for-demonstration-purposes">Print the details (for demonstration purposes)</a></li>
<li><a href="#save-the-data-to-the-django-database-using-the-django-shell">Save the data to the Django database using the Django shell</a></li>
<li><a href="#log-the-details-to-the-output-file">Log the details to the output file</a></li>
<li><a href="#this-line-retrieves-the-directory-path-of-the-current-python-script-admin.py-in-this-case-using-file">This line retrieves the directory path of the current Python script (admin.py in this case) using file,</a></li>
<li><a href="#which-is-a-special-attribute-in-python-that-represents-the-current-file-path.">which is a special attribute in Python that represents the current file path.</a></li>
<li><a href="#create-your-models-here.-mauro">Create your models here. Mauro</a></li>
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
      <h1 id="welcome-to-stackedit">Welcome to StackEdit!</h1>
<p>Ultimo aggiornamento 12/8/24 - h. 17:47<br>
Hi! I’m your first Markdown file in <strong>StackEdit</strong>. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the <strong>file explorer</strong> on the left corner of the navigation bar.</p>
<h1 id="files">Files</h1>
<p>StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible <strong>offline!</strong></p>
<h2 id="create-files-and-folders">Create files and folders</h2>
<p>The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the <strong>New file</strong> button in the file explorer. You can also create folders by clicking the <strong>New folder</strong> button.</p>
<h2 id="switch-to-another-file">Switch to another file</h2>
<p>All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.</p>
<h2 id="rename-a-file">Rename a file</h2>
<p>You can rename the current file by clicking the file name in the navigation bar or by clicking the <strong>Rename</strong> button in the file explorer.</p>
<h2 id="delete-a-file">Delete a file</h2>
<p>You can delete the current file by clicking the <strong>Remove</strong> button in the file explorer. The file will be moved into the <strong>Trash</strong> folder and automatically deleted after 7 days of inactivity.</p>
<h2 id="export-a-file">Export a file</h2>
<p>You can export the current file by clicking <strong>Export to disk</strong> in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.</p>
<h1 id="synchronization">Synchronization</h1>
<p>Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your <strong>Google Drive</strong>, your <strong>Dropbox</strong> and your <strong>GitHub</strong> accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow… The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.</p>
<p>There are two types of synchronization and they can complement each other:</p>
<ul>
<li>
<p>The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.</p>
<blockquote>
<p>To start syncing your workspace, just sign in with Google in the menu.</p>
</blockquote>
</li>
<li>
<p>The file synchronization will keep one file of the workspace synced with one or multiple files in <strong>Google Drive</strong>, <strong>Dropbox</strong> or <strong>GitHub</strong>.</p>
<blockquote>
<p>Before starting to sync files, you must link an account in the <strong>Synchronize</strong> sub-menu.</p>
</blockquote>
</li>
</ul>
<h2 id="open-a-file">Open a file</h2>
<p>You can open a file from <strong>Google Drive</strong>, <strong>Dropbox</strong> or <strong>GitHub</strong> by opening the <strong>Synchronize</strong> sub-menu and clicking <strong>Open from</strong>. Once opened in the workspace, any modification in the file will be automatically synced.</p>
<h2 id="save-a-file">Save a file</h2>
<p>You can save any file of the workspace to <strong>Google Drive</strong>, <strong>Dropbox</strong> or <strong>GitHub</strong> by opening the <strong>Synchronize</strong> sub-menu and clicking <strong>Save on</strong>. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.</p>
<h2 id="synchronize-a-file">Synchronize a file</h2>
<p>Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.</p>
<p>If you just have modified your file and you want to force syncing, click the <strong>Synchronize now</strong> button in the navigation bar.</p>
<blockquote>
<p><strong>Note:</strong> The <strong>Synchronize now</strong> button is disabled if you have no file to synchronize.</p>
</blockquote>
<h2 id="manage-file-synchronization">Manage file synchronization</h2>
<p>Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking <strong>File synchronization</strong> in the <strong>Synchronize</strong> sub-menu. This allows you to list and remove synchronized locations that are linked to your file.</p>
<h1 id="publication">Publication</h1>
<p>Publishing in StackEdit makes it simple for you to publish online your files. Once you’re happy with a file, you can publish it to different hosting platforms like <strong>Blogger</strong>, <strong>Dropbox</strong>, <strong>Gist</strong>, <strong>GitHub</strong>, <strong>Google Drive</strong>, <strong>WordPress</strong> and <strong>Zendesk</strong>. With <a href="http://handlebarsjs.com/">Handlebars templates</a>, you have full control over what you export.</p>
<blockquote>
<p>Before starting to publish, you must link an account in the <strong>Publish</strong> sub-menu.</p>
</blockquote>
<h2 id="publish-a-file">Publish a File</h2>
<p>You can publish your file by opening the <strong>Publish</strong> sub-menu and by clicking <strong>Publish to</strong>. For some locations, you can choose between the following formats:</p>
<ul>
<li>Markdown: publish the Markdown text on a website that can interpret it (<strong>GitHub</strong> for instance),</li>
<li>HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).</li>
</ul>
<h2 id="update-a-publication">Update a publication</h2>
<p>After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the <strong>Publish now</strong> button in the navigation bar.</p>
<blockquote>
<p><strong>Note:</strong> The <strong>Publish now</strong> button is disabled if your file has not been published yet.</p>
</blockquote>
<h2 id="manage-file-publication">Manage file publication</h2>
<p>Since one file can be published to multiple locations, you can list and manage publish locations by clicking <strong>File publication</strong> in the <strong>Publish</strong> sub-menu. This allows you to list and remove publication locations that are linked to your file.</p>
<h1 id="markdown-extensions">Markdown extensions</h1>
<p>StackEdit extends the standard Markdown syntax by adding extra <strong>Markdown extensions</strong>, providing you with some nice features.</p>
<blockquote>
<p><strong>ProTip:</strong> You can disable any <strong>Markdown extension</strong> in the <strong>File properties</strong> dialog.</p>
</blockquote>
<h2 id="smartypants">SmartyPants</h2>
<p>SmartyPants converts ASCII punctuation characters into “smart” typographic punctuation HTML entities. For example:</p>

<table>
<thead>
<tr>
<th></th>
<th>ASCII</th>
<th>HTML</th>
</tr>
</thead>
<tbody>
<tr>
<td>Single backticks</td>
<td><code>'Isn't this fun?'</code></td>
<td>‘Isn’t this fun?’</td>
</tr>
<tr>
<td>Quotes</td>
<td><code>"Isn't this fun?"</code></td>
<td>“Isn’t this fun?”</td>
</tr>
<tr>
<td>Dashes</td>
<td><code>-- is en-dash, --- is em-dash</code></td>
<td>– is en-dash, — is em-dash</td>
</tr>
</tbody>
</table><h2 id="katex">KaTeX</h2>
<p>You can render LaTeX mathematical expressions using <a href="https://khan.github.io/KaTeX/">KaTeX</a>:</p>
<p>The <em>Gamma function</em> satisfying <span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi mathvariant="normal">Γ</mi><mo stretchy="false">(</mo><mi>n</mi><mo stretchy="false">)</mo><mo>=</mo><mo stretchy="false">(</mo><mi>n</mi><mo>−</mo><mn>1</mn><mo stretchy="false">)</mo><mo stretchy="false">!</mo><mspace width="1em"></mspace><mi mathvariant="normal">∀</mi><mi>n</mi><mo>∈</mo><mi mathvariant="double-struck">N</mi></mrow><annotation encoding="application/x-tex">\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mord">Γ</span><span class="mopen">(</span><span class="mord mathnormal">n</span><span class="mclose">)</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal">n</span><span class="mspace" style="margin-right: 0.222222em;"></span><span class="mbin">−</span><span class="mspace" style="margin-right: 0.222222em;"></span></span><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mord">1</span><span class="mclose">)!</span><span class="mspace" style="margin-right: 1em;"></span><span class="mord">∀</span><span class="mord mathnormal">n</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">∈</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 0.68889em; vertical-align: 0em;"></span><span class="mord mathbb">N</span></span></span></span></span> is via the Euler integral</p>
<p><span class="katex--display"><span class="katex-display"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><semantics><mrow><mi mathvariant="normal">Γ</mi><mo stretchy="false">(</mo><mi>z</mi><mo stretchy="false">)</mo><mo>=</mo><msubsup><mo>∫</mo><mn>0</mn><mi mathvariant="normal">∞</mi></msubsup><msup><mi>t</mi><mrow><mi>z</mi><mo>−</mo><mn>1</mn></mrow></msup><msup><mi>e</mi><mrow><mo>−</mo><mi>t</mi></mrow></msup><mi>d</mi><mi>t</mi> <mi mathvariant="normal">.</mi></mrow><annotation encoding="application/x-tex">
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mord">Γ</span><span class="mopen">(</span><span class="mord mathnormal" style="margin-right: 0.04398em;">z</span><span class="mclose">)</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">=</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 2.32624em; vertical-align: -0.91195em;"></span><span class="mop"><span class="mop op-symbol large-op" style="margin-right: 0.44445em; position: relative; top: -0.001125em;">∫</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 1.41429em;"><span class="" style="top: -1.78805em; margin-left: -0.44445em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">0</span></span></span><span class="" style="top: -3.8129em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">∞</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.91195em;"><span class=""></span></span></span></span></span></span><span class="mspace" style="margin-right: 0.166667em;"></span><span class="mord"><span class="mord mathnormal">t</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height: 0.864108em;"><span class="" style="top: -3.113em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathnormal mtight" style="margin-right: 0.04398em;">z</span><span class="mbin mtight">−</span><span class="mord mtight">1</span></span></span></span></span></span></span></span></span><span class="mord"><span class="mord mathnormal">e</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height: 0.843556em;"><span class="" style="top: -3.113em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">−</span><span class="mord mathnormal mtight">t</span></span></span></span></span></span></span></span></span><span class="mord mathnormal">d</span><span class="mord mathnormal">t</span><span class="mspace" style="margin-right: 0.166667em;"></span><span class="mord">.</span></span></span></span></span></span></p>
<blockquote>
<p>You can find more information about <strong>LaTeX</strong> mathematical expressions <a href="http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference">here</a>.</p>
</blockquote>
<h2 id="uml-diagrams">UML diagrams</h2>
<p>You can render UML diagrams using <a href="https://mermaidjs.github.io/">Mermaid</a>. For example, this will produce a sequence diagram:</p>
<pre class=" language-mermaid"><svg id="mermaid-svg-J722GNiAnJJTFhoK" width="100%" xmlns="http://www.w3.org/2000/svg" height="519" style="max-width: 819px;" viewBox="-50 -10 819 519"><style>#mermaid-svg-J722GNiAnJJTFhoK{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}#mermaid-svg-J722GNiAnJJTFhoK .error-icon{fill:#552222;}#mermaid-svg-J722GNiAnJJTFhoK .error-text{fill:#552222;stroke:#552222;}#mermaid-svg-J722GNiAnJJTFhoK .edge-thickness-normal{stroke-width:2px;}#mermaid-svg-J722GNiAnJJTFhoK .edge-thickness-thick{stroke-width:3.5px;}#mermaid-svg-J722GNiAnJJTFhoK .edge-pattern-solid{stroke-dasharray:0;}#mermaid-svg-J722GNiAnJJTFhoK .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-svg-J722GNiAnJJTFhoK .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-svg-J722GNiAnJJTFhoK .marker{fill:#666;stroke:#666;}#mermaid-svg-J722GNiAnJJTFhoK .marker.cross{stroke:#666;}#mermaid-svg-J722GNiAnJJTFhoK svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-svg-J722GNiAnJJTFhoK .actor{stroke:hsl(0,0%,83%);fill:#eee;}#mermaid-svg-J722GNiAnJJTFhoK text.actor > tspan{fill:#333;stroke:none;}#mermaid-svg-J722GNiAnJJTFhoK .actor-line{stroke:#666;}#mermaid-svg-J722GNiAnJJTFhoK .messageLine0{stroke-width:1.5;stroke-dasharray:none;stroke:#333;}#mermaid-svg-J722GNiAnJJTFhoK .messageLine1{stroke-width:1.5;stroke-dasharray:2,2;stroke:#333;}#mermaid-svg-J722GNiAnJJTFhoK #arrowhead path{fill:#333;stroke:#333;}#mermaid-svg-J722GNiAnJJTFhoK .sequenceNumber{fill:white;}#mermaid-svg-J722GNiAnJJTFhoK #sequencenumber{fill:#333;}#mermaid-svg-J722GNiAnJJTFhoK #crosshead path{fill:#333;stroke:#333;}#mermaid-svg-J722GNiAnJJTFhoK .messageText{fill:#333;stroke:#333;}#mermaid-svg-J722GNiAnJJTFhoK .labelBox{stroke:hsl(0,0%,83%);fill:#eee;}#mermaid-svg-J722GNiAnJJTFhoK .labelText,#mermaid-svg-J722GNiAnJJTFhoK .labelText > tspan{fill:#333;stroke:none;}#mermaid-svg-J722GNiAnJJTFhoK .loopText,#mermaid-svg-J722GNiAnJJTFhoK .loopText > tspan{fill:#333;stroke:none;}#mermaid-svg-J722GNiAnJJTFhoK .loopLine{stroke-width:2px;stroke-dasharray:2,2;stroke:hsl(0,0%,83%);fill:hsl(0,0%,83%);}#mermaid-svg-J722GNiAnJJTFhoK .note{stroke:hsl(60,100%,23.3333333333%);fill:#ffa;}#mermaid-svg-J722GNiAnJJTFhoK .noteText,#mermaid-svg-J722GNiAnJJTFhoK .noteText > tspan{fill:#333;stroke:none;}#mermaid-svg-J722GNiAnJJTFhoK .activation0{fill:#f4f4f4;stroke:#666;}#mermaid-svg-J722GNiAnJJTFhoK .activation1{fill:#f4f4f4;stroke:#666;}#mermaid-svg-J722GNiAnJJTFhoK .activation2{fill:#f4f4f4;stroke:#666;}#mermaid-svg-J722GNiAnJJTFhoK:root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}#mermaid-svg-J722GNiAnJJTFhoK sequence{fill:apa;}</style><g></g><g><line id="actor12" x1="75" y1="5" x2="75" y2="508" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="0" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="75" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="75" dy="0">Alice</tspan></text></g><g><line id="actor13" x1="319" y1="5" x2="319" y2="508" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="244" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="319" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="319" dy="0">Bob</tspan></text></g><g><line id="actor14" x1="544" y1="5" x2="544" y2="508" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="469" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="544" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="544" dy="0">John</tspan></text></g><defs><marker id="arrowhead" refX="9" refY="5" markerUnits="userSpaceOnUse" markerWidth="12" markerHeight="12" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z"></path></marker></defs><defs><marker id="crosshead" markerWidth="15" markerHeight="8" orient="auto" refX="16" refY="4"><path fill="black" stroke="#000000" stroke-width="1px" d="M 9,2 V 6 L16,4 Z" style="stroke-dasharray: 0, 0;"></path><path fill="none" stroke="#000000" stroke-width="1px" d="M 0,1 L 6,7 M 6,1 L 0,7" style="stroke-dasharray: 0, 0;"></path></marker></defs><defs><marker id="filled-head" refX="18" refY="7" markerWidth="20" markerHeight="28" orient="auto"><path d="M 18,7 L9,13 L14,7 L9,1 Z"></path></marker></defs><defs><marker id="sequencenumber" refX="15" refY="15" markerWidth="60" markerHeight="40" orient="auto"><circle cx="15" cy="15" r="6"></circle></marker></defs><text x="197" y="80" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">Hello Bob, how are you?</text><line x1="75" y1="109" x2="319" y2="109" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="fill: none;"></line><text x="432" y="124" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">How about you John?</text><line x1="319" y1="153" x2="544" y2="153" class="messageLine1" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="stroke-dasharray: 3, 3; fill: none;"></line><text x="197" y="168" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">I am good thanks!</text><line x1="319" y1="197" x2="75" y2="197" class="messageLine1" stroke-width="2" stroke="none" marker-end="url(#crosshead)" style="stroke-dasharray: 3, 3; fill: none;"></line><text x="432" y="212" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">I am good thanks!</text><line x1="319" y1="241" x2="544" y2="241" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#crosshead)" style="fill: none;"></line><g><rect x="569" y="251" fill="#EDF2AE" stroke="#666" width="150" height="84" rx="0" ry="0" class="note"></rect><text x="644" y="256" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="noteText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 14px; font-weight: 400;"><tspan x="644">Bob thinks a long</tspan></text><text x="644" y="272" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="noteText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 14px; font-weight: 400;"><tspan x="644">long time, so long</tspan></text><text x="644" y="288" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="noteText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 14px; font-weight: 400;"><tspan x="644">that the text does</tspan></text><text x="644" y="304" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="noteText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 14px; font-weight: 400;"><tspan x="644">not fit on a row.</tspan></text></g><text x="197" y="350" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">Checking with John...</text><line x1="319" y1="379" x2="75" y2="379" class="messageLine1" stroke-width="2" stroke="none" style="stroke-dasharray: 3, 3; fill: none;"></line><text x="310" y="394" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">Yes... John, how are you?</text><line x1="75" y1="423" x2="544" y2="423" class="messageLine0" stroke-width="2" stroke="none" style="fill: none;"></line><g><rect x="0" y="443" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="75" y="475.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="75" dy="0">Alice</tspan></text></g><g><rect x="244" y="443" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="319" y="475.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="319" dy="0">Bob</tspan></text></g><g><rect x="469" y="443" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="544" y="475.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="544" dy="0">John</tspan></text></g></svg></pre>
<p>And this will produce a flow chart:</p>
<pre class=" language-mermaid"><code class="prism  language-mermaid">graph LR
A[Square Rect] -- Link text --&gt; B((Circle))
A --&gt; C(Round Rect)
B --&gt; D{Rhombus}
C --&gt; D
```[toc]


# MARKUP HINTS
By Mauro alle h. 06 12 maggio 24
I have my README.md inside my project. Here are a method to work with your README.md separately while working on your vsc local project: Use an external Markdown editor like 

[Typora]: (https://typora.io/#feature)

** (a minimal markdown editor and reader) **. These editors provide a live preview feature by default. 

# BASH

- trovare la oporta occupata:
  - `lsof -i :8000`
  
- chiudere la porta occupata forzatamente:
  - `kill -9 32394(esempio)`
  
- vedere i comandi che iniziano per una determinata strina effettuati in precedenza:
  -  `history | grep "kill (esempio)"`

- trovare la porta occupata:
  - `lsof -i :8000`
  
- chiudere la porta occupata forzatamente:
  - `kill -9 32394(esempio)`
  
- vedere i comandi che iniziano per una determinata strina effettuati in precedenza:
  -  `history | grep "kill (esempio)"`
  
- Azione Bash - Quello che segue è uno script molto importante che permette nell'ordine di 1) verificare se la porta 8000 (che viene utilizzata normalmente in fase di sviluppo) è occupata ed eventualmente chiuderla; 2) aprire Django 3) aprire hugo. Al momento sono presenti due file separati per una migliore comprensione:
```bash
- check_ports.sh

  \#!/bin/bash

  \# Check if any process is listening on port 8000

  if lsof -i :8000 &gt;/dev/null 2&gt;&amp;1; then

  ​    echo "Port 8000 is in use."

  ​    \# Get the PID of the process using port 8000

  ​    pid=$(lsof -ti :8000)

  ​    \# Kill the process

  ​    echo "Killing process with PID $pid"

  ​    kill -9 "$pid"

  ​    echo "Process killed."

  else

  ​    echo "Port 8000 is not in use."

  fi
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
<h2 id="the-subprocess-module-wrapping-programs-with-python">THE subprocess Module: Wrapping Programs With Python</h2>
<p>If you’ve ever wanted to simplify your command-line scripting or use Python alongside command-line applications—or any applications for that matter—then the Python <code>subprocess</code> module can help. From running shell commands and command-line applications to launching applications, the Python <code>subprocess</code> module can help.</p>
<h3 id="processes-and-subprocesses">Processes and Subprocesses</h3>
<p>First off, you might be wondering why there’s a  <code>sub</code>  in the Python  <code>subprocess</code>  module name. And what exactly is a process, anyway?<br>
Whenever you use a computer, you’ll always be interacting with programs. A  <strong>process</strong>  is the operating system’s abstraction of a running program. So, using a computer always involve processes. Start menus, app bars, command-line interpreters, text editors, browsers, and more—every application comprises one or more processes.</p>
<p>A typical operating system will report hundreds or even thousands of running processes. However, central  <em>processing</em>  units (CPUs) typically only have a handful of cores, which means that they can only run a handful of instructions simultaneously. So, you may wonder how thousands of processes can appear to run at the same time.</p>
<p>In short, the operating system is a marvelous multitasker—as it has to be. The CPU is the brain of a computer, but it operates at the  timescale. Most other components of a computer are far slower than the CPU. For instance, a magnetic hard disk read takes thousands of times longer than a typical CPU operation.</p>
<p>If a process needs to write something to the hard drive, or wait for a response from a remote server, then the CPU would sit idle  <em>most of the time</em>. Multitasking keeps the CPU busy.</p>
<p>Part of what makes the operating system so great at multitasking is that it’s fantastically organized too. The operating system keeps track of processes in a process table or  <a href="https://en.wikipedia.org/wiki/Process_control_block">process control block</a>. In this table, you’ll find the process’s  <a href="https://realpython.com/why-close-file-python/#in-short-files-are-resources-limited-by-the-operating-system">file handles</a>, security context, references to its  <a href="https://en.wikipedia.org/wiki/Address_space">address spaces</a>, and more.</p>
<p>The process table allows the operating system to abandon a particular process at will, because it has all the information it needs to come back and continue with the process at a later time. A process may be interrupted many thousands of times during execution, but the operating system always finds the exact point where it left off upon returning.</p>
<p>An operating system doesn’t boot up with thousands of processes, though. Many of the processes you’re familiar with are started by you. In the next section, you’ll look into the lifetime of a process.</p>
<h3 id="process-lifetime">Process Lifetime</h3>
<p>Think of how you might start a Python application from the command line. This is an instance of your command-line  <em>process</em>  starting a Python  <em>process</em>:</p>
<p><a href="https://files.realpython.com/media/Peek_2022-05-06_11-31.b24eb35f6ed0.gif"><img src="https://files.realpython.com/media/Peek_2022-05-06_11-31.b24eb35f6ed0.gif" alt="Animation of basic process creation"></a></p>
<p>The process that starts another process is referred to as the  <strong>parent</strong>, and the new process is referred to as the  <strong>child</strong>. The parent and child processes run mostly independently. Sometimes the child inherits specific resources or contexts from the parentand nformation about processes is kept in a table. Each process keeps track of its parents, which allows the process hierarchy to be represented as a tree.</p>
<h3 id="process-creation-mechanism-on-unix-based-systems">Process Creation Mechanism on Unix-based Systems</h3>
<p>Here’s a breakdown of the process creation mechanism on Unix-based systems, focusing on the key concepts and functionalities:</p>
<p><strong>1. fork() System Call:</strong></p>
<ul>
<li>The foundation of process creation in Unix systems is the <code>fork()</code> system call.</li>
<li>When a process calls <code>fork()</code>, the kernel creates a <strong>copy</strong> of the calling process. This copy is called the <strong>child process</strong>, while the original process becomes the <strong>parent process</strong>.</li>
<li>Both parent and child processes share the same memory space initially. This might seem inefficient, but it allows for quick process creation and efficient memory sharing when needed.</li>
</ul>
<p><strong>2. Process Identifier (PID):</strong></p>
<ul>
<li>The kernel assigns a unique identifier, called a <strong>Process Identifier (PID)</strong>, to each process. This PID helps the system differentiate between processes and manage their resources.</li>
<li>After the <code>fork()</code> call, both the parent and child process receive the PID of the child process as the return value. However, they can distinguish their own identity using functions like <code>getpid()</code>.</li>
</ul>
<p><strong>3. The Exec Family of Functions:</strong></p>
<ul>
<li>Once a child process is created with <code>fork()</code>, it typically doesn’t continue executing the original program’s code.</li>
<li>The child process usually replaces its code and data space with a new program using functions like <code>execve()</code>, <code>execvp()</code>, or others from the <code>exec</code> family.</li>
<li>These functions take the path to the executable file and optional arguments as input.</li>
<li>By replacing its code with the new program, the child process essentially starts executing a completely different program.</li>
</ul>
<p><strong>4. Memory Management:</strong></p>
<ul>
<li>After <code>fork()</code>, the parent and child processes share the same memory space. However, any changes made by one process are not reflected immediately in the other’s memory.</li>
<li>When either process modifies memory, a technique called <strong>copy-on-write</strong> is employed. The kernel creates a copy of the modified memory page for the modifying process, allowing them to have independent memory regions for further changes.</li>
</ul>
<p><strong>5. Resource Inheritance:</strong></p>
<ul>
<li>The child process inherits most resources from the parent process, including file descriptors, open files, signal handlers (with some exceptions), and environment variables. This inheritance simplifies program execution as the child process inherits a ready-made environment.</li>
</ul>
<p><strong>Overall Flow:</strong></p>
<ol>
<li>Parent process calls <code>fork()</code>.</li>
<li>Kernel creates a copy of the parent process (child process).</li>
<li>Both parent and child receive the child’s PID.</li>
<li>Child process usually replaces its code with a new program using <code>exec</code> functions.</li>
<li>Memory management employs copy-on-write to maintain independent memory spaces for parent and child.</li>
<li>Child process inherits most resources from the parent.</li>
</ol>
<p><strong>Additional Notes:</strong></p>
<ul>
<li>This explanation provides a basic overview. There are additional details and complexities involved in process creation, like process states, scheduling, and signals.</li>
<li>The <code>wait()</code> system call allows the parent process to wait for the child process to finish execution.</li>
<li>Inter-process communication (IPC) mechanisms enable processes to communicate and share data after creation.</li>
</ul>
<p>This knowledge should provide a solid foundation for understanding process creation on Unix-based systems. You can explore further details in resources like the Unix man pages for <code>fork()</code>, <code>exec</code>, and related functions.</p>
<h3 id="interaction-with-fork-with-user--application-oshardware">Interaction with fork() with user / application /OS/Hardware</h3>
<p><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Operating_system_placement.svg/165px-Operating_system_placement.svg.png" alt=""><br>
<code>fork</code> system call interacts with these components on a Unix-based system:</p>
<p><strong>1. User Initiates Action:</strong></p>
<ul>
<li>The process starts with a user initiating an action. This could involve launching an application or performing some task within an existing application.</li>
</ul>
<p><strong>2. Application Requests New Process (Optional):</strong></p>
<ul>
<li>The application itself might not directly call <code>fork</code>. However, in some cases, an application might request the creation of a new process to handle a specific subtask within the application. This would involve the application making a system call (not directly <code>fork</code> itself) to the operating system to create a new process.</li>
</ul>
<p><strong>3. Operating System Kernel and fork():</strong></p>
<ul>
<li>The core interaction happens at the operating system kernel level. When <code>fork()</code> is called (either by the application or the kernel itself for some reason), the kernel creates a copy of the existing process. This copied process is called the child process, and the original process becomes the parent process.</li>
</ul>
<p><strong>4. Memory and Resource Management:</strong></p>
<ul>
<li>The kernel needs to manage resources for both the parent and child processes. This includes memory, CPU time, and access to devices.</li>
<li>Initially, both parent and child processes share the same memory space. However, a technique called copy-on-write (COW) is often used to optimize memory usage. With COW, memory pages are only copied when either process tries to modify them.</li>
</ul>
<p><strong>5. Hardware and Process Execution:</strong></p>
<ul>
<li>The hardware itself (CPU, memory, devices) doesn’t directly understand <code>fork</code>. It operates based on instructions provided by the kernel.</li>
<li>The kernel manages the context switching between the parent and child processes, ensuring each gets a slice of CPU time to execute instructions.</li>
</ul>
<p><strong>Overall Interaction Summary:</strong></p>
<p>The <code>fork</code> system call primarily interacts with the operating system kernel. It triggers the creation of a new process and the kernel manages the resource allocation (including memory) for both parent and child processes. The hardware executes instructions provided by the kernel for both processes, and the kernel employs context switching to ensure efficient CPU utilization.</p>
<p><strong>Important Note:</strong></p>
<p>The diagram you sent depicts a high-level view of system components. The <code>fork</code> system call and process creation happen within the operating system kernel, which is not explicitly shown in the diagram.</p>
<h3 id="flow-representing-the-fork-system-call-at-the-kernel-level-on-unix-based-systems">Flow representing the <code>fork</code> system call at the kernel level on Unix-based systems:</h3>
<p><strong>Components:</strong></p>
<ol>
<li><strong>Parent Process:</strong> This represents the existing process before calling <code>fork</code>. It has its own memory space, registers, and program counter (PC) holding the current instruction.</li>
<li><strong>Kernel (Fork System Call):</strong> This symbolizes the core of the operating system responsible for handling <code>fork</code>.</li>
<li><strong>Process Descriptor Table (PDT):</strong> This table maintains information about all processes in the system, including the parent process.</li>
<li><strong>Memory Management Unit (MMU):</strong> This hardware component translates virtual addresses used by processes to physical memory addresses.</li>
<li><strong>Memory (Code, Data, Stack):</strong> This represents the memory space containing the program code, data, and stack of the parent process.</li>
</ol>
<p><strong>Process of <code>fork</code>:</strong></p>
<ol>
<li><strong><code>fork</code> System Call:</strong> The parent process initiates the <code>fork</code> system call through a system call interface.</li>
<li><strong>Kernel Creates Child Process Descriptor:</strong> The kernel allocates a new entry in the Process Descriptor Table (PDT) for the child process. This entry will hold information about the child process, including its state and resources.</li>
<li><strong>Memory Space Copying (Logical):</strong> The kernel doesn’t physically copy the entire memory space of the parent process initially. Instead, it creates a copy of the memory mappings for the child process in the MMU. Both parent and child processes share the same physical memory pages until one of them tries to modify the data.</li>
<li><strong>Registers and Program Counter Copying:</strong> The kernel copies the values of all CPU registers from the parent process to the child process. This ensures the child process starts execution at the same instruction point as the parent process when it called <code>fork</code>.</li>
<li><strong>New File Descriptors and Resources:</strong> The kernel allocates new file descriptors and other resources (like open network connections) for the child process. These resources might be shared or duplicated depending on the specific resource type.</li>
</ol>
<p><strong>Post-<code>fork</code> State:</strong></p>
<ul>
<li>The parent and child processes now exist as independent entities with their own process descriptors, memory mappings, and registers.</li>
<li>They share the same physical memory pages initially (through copy-on-write), but any modifications by either process will trigger a copy of the modified page for that specific process.</li>
<li>Both processes are typically in a “ready” state, waiting to be scheduled for CPU execution by the kernel.</li>
</ul>
<p><strong>Additional Notes:</strong></p>
<ul>
<li>This is a simplified diagram, and the actual implementation of <code>fork</code> can vary depending on the specific operating system.</li>
<li>The diagram doesn’t show the hardware itself (CPU, memory) but represents the interaction through the MMU.</li>
<li>Context switching between parent and child processes is managed by the kernel after <code>fork</code>.</li>
</ul>
<p>I hope this visual representation provides a clearer understanding of how <code>fork</code> works at the kernel level. Feel free to ask if you have any further questions about specific details in the diagram.</p>
<p>The parent-child relationship between a process and its subprocess isn’t always the same. Sometimes the two processes will share specific resources, like inputs and outputs, but sometimes they won’t. Sometimes child processes live longer than the parent. A child outliving the parent can lead to  <a href="https://en.wikipedia.org/wiki/Orphan_process">orphaned</a>  or  <a href="https://en.wikipedia.org/wiki/Zombie_process">zombie</a>  processes, though more discussion about those is outside the scope of this tutorial.</p>
<p>When a process has finished running, it’ll usually end. Every process, on exit, should return an integer. This integer is referred to as the  <strong>return code</strong>  or  <a href="https://en.wikipedia.org/wiki/Exit_status">exit status</a>. Zero is synonymous with success, while any other value is considered a failure. Different integers can be used to indicate the reason why a process has failed.</p>
<p>In the same way that you can return a value from a function in Python, the operating system expects an integer return value from a process once it exits. This is why the canonical  <a href="https://en.wikipedia.org/wiki/C_(programming_language)">C</a>  <code>main()</code>  function usually returns an integer:</p>
<pre><code>C

`// minimal_program.c

int  main(){
  return  0;
}` 
</code></pre>
<p>This example shows a minimal amount of C code necessary for the file to compile with  <a href="https://gcc.gnu.org/"><code>gcc</code></a>  without any warnings. It has a  <code>main()</code>  function that returns an integer. When this program runs, the operating system will interpret its execution as successful since it returns zero.</p>
<h3 id="active-processes-on-your-system">Active Processes on Your System<a href="https://realpython.com/python-subprocess/#active-processes-on-your-system" title="Permanent link"></a></h3>
<p>You may be curious to see what processes are running on your system right now. To do that, you can use platform-specific utilities to track them:</p>
<ul>
<li><a href="https://realpython.com/python-subprocess/#windows-1">Windows</a></li>
<li><a href="https://realpython.com/python-subprocess/#linux-macos-1">Linux + macOS</a></li>
</ul>
<p>For UNIX-based systems, there are many command-line utilities to choose from:</p>
<ul>
<li><a href="https://man7.org/linux/man-pages/man1/top.1.html"><code>top</code></a>: The classic process and resource monitor, often installed by default. Once it’s running, to see the tree view, also called the forest view, press  Shift+V. The forest view may not work on the default macOS  <code>top</code>.</li>
<li><a href="https://htop.dev/"><code>htop</code></a>: More advanced and user-friendly version of  <code>top</code>.</li>
<li><a href="https://man7.org/linux/man-pages/man1/pcp-atop.1.html"><code>atop</code></a>: Another version of  <code>top</code>  with more information, but more technical.</li>
<li><a href="https://pypi.org/project/bpytop/"><code>bpytop</code></a>: A Python implementation of  <code>top</code>  with nice visuals.</li>
<li><a href="https://en.wikipedia.org/wiki/Pstree"><code>pstree</code></a>: A utility specifically to explore the process tree.</li>
</ul>
<p>On macOS, you also have the  <a href="https://support.apple.com/guide/activity-monitor/welcome/mac">Activity Monitor</a>  application in your utilities. In the View menu, if you select  <em>All Processes, Hierarchically</em>, you should be able to see your process tree.</p>
<p>You can also explore the Python  <a href="https://github.com/giampaolo/psutil">psutil</a>  library, which allows you to retrieve running process information on both Windows and UNIX-based systems.</p>
<p>One universal attribute of process tracking across systems is that each process has a  <strong>process identification number</strong>, or  <strong>PID</strong>, which is a unique integer to identify the process within the context of the operating system. You’ll see this number on most of the utilities listed above.</p>
<p>Along with the PID, it’s typical to see the resource usage, such as  <a href="https://en.wikipedia.org/wiki/Central_processing_unit">CPU</a>  percentage and amount of  <a href="https://en.wikipedia.org/wiki/Random-access_memory">RAM</a>  that a particular process is using. This is the information that you look for if a program is hogging all your resources.</p>
<p>The resource utilization of processes can be useful for developing or debugging scripts that use the  <code>subprocess</code>  module, even though you don’t need the PID, or any information about what resources processes are using in the code itself. While playing with the examples that are coming up, consider leaving a representation of the process tree open to see the new processes pop up.</p>
<p>You now have a bird’s-eye view of processes. You’ll deepen your mental model throughout the tutorial, but now it’s time to see how to start your own processes with the Python  <code>subprocess</code>  module.</p>
<h2 id="overview-of-the-python--subprocess--module">Overview of the Python  <code>subprocess</code>  Module</h2>
<p>The Python  <code>subprocess</code>  module is for launching child processes. These processes can be anything from GUI applications to the shell. The parent-child relationship of processes is where the  <strong>sub</strong>  in the  <code>subprocess</code>  name comes from. When you use  <code>subprocess</code>, Python is the parent that creates a new child process. What that new child process is, is up to you.</p>
<p>Python  <code>subprocess</code>  was  <a href="https://peps.python.org/pep-0324/">originally proposed and accepted</a>  for Python 2.4 as an alternative to using the  <a href="https://docs.python.org/3/library/os.html"><code>os</code>  module</a>. Some documented changes have happened as late as 3.8. The examples in this article were tested with Python 3.10.4, but you only need 3.8+ to follow along with this tutorial.</p>
<p>Most of your interaction with the Python  <code>subprocess</code>  module will be via the  <a href="https://docs.python.org/3/library/subprocess.html#subprocess.run"><code>run()</code></a>  function. This  <a href="https://en.wikipedia.org/wiki/Blocking_(computing)">blocking</a>  function will start a process and  <em>wait</em>  until the new process exits before moving on.</p>
<p>The  <a href="https://docs.python.org/3/library/subprocess.html#using-the-subprocess-module">documentation</a>  recommends using  <code>run()</code>  for all cases that it can handle. For edge cases where you need more control, the  <a href="https://docs.python.org/3/library/subprocess.html#subprocess.Popen"><code>Popen</code></a>  class can be used.  <code>Popen</code>  is the underlying class for the whole  <code>subprocess</code>  module. All functions in the  <code>subprocess</code>  module are convenience wrappers around the  <code>Popen()</code>  constructor and its instance methods. Near the end of this tutorial, you’ll  <a href="https://realpython.com/python-subprocess/#the-popen-class">dive into</a>  the  <code>Popen</code>  class.<br>
You may come across other functions like  <a href="https://docs.python.org/3/library/subprocess.html#subprocess.call"><code>call()</code></a>,  <a href="https://docs.python.org/3/library/subprocess.html#subprocess.check_call"><code>check_call()</code></a>, and  <a href="https://docs.python.org/3/library/subprocess.html#subprocess.check_output"><code>check_output()</code></a>, but these belong to the older  <code>subprocess</code>  <a href="https://en.wikipedia.org/wiki/API">API</a>  from Python 3.5 and earlier. Everything these three functions do can be replicated with the newer  <code>run()</code>  function. The older API is mainly still there for backwards compatibility, and you won’t cover it in this tutorial.</p>
<p>There’s also a fair amount of redundancy in the  <code>subprocess</code>  module, meaning that there are various ways to achieve the same end goal. You won’t be exploring all variations in this tutorial. What you will find, though, are robust techniques that should keep you on the right path.</p>
<h2 id="basic-usage-of-the-python--subprocess--module">Basic Usage of the Python  <code>subprocess</code>  Module</h2>
<p>In this section, you’ll take a look at some of the most basic examples demonstrating the usage of the  <code>subprocess</code>  module. You’ll start by exploring a bare-bones command-line timer program with the  <code>run()</code>  function.</p>
<h2 id="basic-usage-of-the-python--subprocess">Basic Usage of the Python  <code>subprocess</code></h2>
<p>In this section, you’ll take a look at some of the most basic examples demonstrating the usage of the  <code>subprocess</code>  module. You’ll start by exploring a bare-bones command-line timer program with the  <code>run()</code>  function.</p>
<h3 id="the-timer-example">The Timer Example</h3>
<p>To come to grips with the Python  <code>subprocess</code>  module, you’ll want a bare-bones program to run and experiment with. For this, you’ll use a program written in Python:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span>  argparse  <span class="token keyword">import</span>  ArgumentParser

<span class="token keyword">from</span>  time  <span class="token keyword">import</span>  sleep

  

parser  <span class="token operator">=</span>  ArgumentParser<span class="token punctuation">(</span><span class="token punctuation">)</span>

parser<span class="token punctuation">.</span>add_argument<span class="token punctuation">(</span><span class="token string">"duration"</span><span class="token punctuation">,</span> <span class="token builtin">type</span><span class="token operator">=</span><span class="token builtin">int</span><span class="token punctuation">)</span> <span class="token comment"># Changed argument name to "duration"</span>

args  <span class="token operator">=</span>  parser<span class="token punctuation">.</span>parse_args<span class="token punctuation">(</span><span class="token punctuation">)</span>

<span class="token keyword">print</span><span class="token punctuation">(</span>f<span class="token string">"Starting timer of {args.duration} seconds"</span><span class="token punctuation">)</span>

<span class="token keyword">for</span>  _  <span class="token keyword">in</span>  <span class="token builtin">range</span><span class="token punctuation">(</span>args<span class="token punctuation">.</span>duration<span class="token punctuation">)</span><span class="token punctuation">:</span>

<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"**"</span><span class="token punctuation">,</span> end<span class="token operator">=</span><span class="token string">""</span><span class="token punctuation">,</span> flush<span class="token operator">=</span><span class="token boolean">True</span><span class="token punctuation">)</span>

sleep<span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">)</span>

<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Bravo Mauuro!"</span><span class="token punctuation">)</span> ```
</code></pre>
<p>enter code hereThe timer program uses  to accept an integer as an argument. The integer represents the number of seconds that the timer should wait until exiting, which the program uses  <a href="https://realpython.com/python-sleep/"><code>sleep()</code></a>  to achieve. It’ll play a small animation representing each passing second until it exits:</p>
<p>It’s not much, but the key is that it serves as a cross-platform process that runs for a few seconds and which you can easily tinker with. You’ll be calling it with  <code>subprocess</code>  as if it were a separate executable.</p>
<p>Each item in the sequence represents a  <a href="https://en.wikipedia.org/wiki/Lexical_analysis#Token">token</a>  which is used for a system call to start a new process.</p>
<h3 id="the-use-of--subprocess--to-run-any-app">The Use of  <code>subprocess</code>  to Run Any App<a href="https://realpython.com/python-subprocess/#the-use-of-subprocess-to-run-any-app" title="Permanent link"></a></h3>
<p>With  <code>subprocess</code>, you aren’t limited to text-based applications like the shell. You can call any application that you can with the Start menu or app bar, as long as you know the precise name or path of the program that you want to run:</p>
<p>Python</p>
<p><code>&gt;&gt;&gt; subprocess.run(["gedit"]) CompletedProcess(args=['gedit'], returncode=0)</code></p>
<p>Depending on your Linux distribution, you may have a different text editor, such as  <code>kate</code>,  <code>leafpad</code>,  <code>kwrite</code>, or  <code>enki</code>.</p>
<p>These commands should open up a text editor window. Usually  <code>CompletedProcess</code>  won’t get returned until you close the editor window. Yet in the case of macOS, since you need to run the launcher process  <a href="https://ss64.com/osx/open.html"><code>open</code></a>  to launch  <a href="https://support.apple.com/guide/textedit/welcome/mac">TextEdit</a>, the  <code>CompletedProcess</code>  gets returned straight away.</p>
<p>Launcher processes are in charge of launching a specific process and then ending. Sometimes programs, such as web browsers, have them built in. The mechanics of launcher processes is out of the scope of this tutorial, but suffice to say that they’re able to manipulate the operating system’s process tree to reassign parent-child relationships.</p>
<p><strong>Note:</strong>  There are many problems that you might initially reach for  <code>subprocess</code>  to solve, but then you’ll find a specific module or library that solves it for you. This tends to be a theme with  <code>subprocess</code>  since it is quite a low-level utility.</p>
<p>An example of something that you might want to do with  <code>subprocess</code>  is to open a web browser to a specific page. However, for that, it’s probably best to use the Python module  <a href="https://docs.python.org/3/library/webbrowser.html"><code>webbrowser</code></a>. The  <code>webbrowser</code>  module uses  <code>subprocess</code>  <a href="https://github.com/python/cpython/blob/3.10/Lib/webbrowser.py#L9">under the hood</a>  but handles all the finicky cross-platform and browser differences that you might encounter.</p>
<p>Then again,  <code>subprocess</code>  can be a remarkably useful tool to get something done quickly. If you don’t need a full-fledged library, then  <code>subprocess</code>  can be your  <a href="https://en.wikipedia.org/wiki/Swiss_Army_knife">Swiss Army knife</a>. It all depends on your use case. More discussion on this topic will come  <a href="https://realpython.com/python-subprocess/#use-cases-for-the-shell-and-subprocess">later</a>.</p>
<p>You’ve successfully started new processes using Python! That’s  <code>subprocess</code>  at its most basic. Next up, you’ll take a closer look at the  <code>CompletedProcess</code>  object that’s returned from  <code>run()</code>.</p>
<h3 id="the--completedprocess--object">The  <code>CompletedProcess</code>  Object<a href="https://realpython.com/python-subprocess/#the-completedprocess-object" title="Permanent link"></a></h3>
<p>When you use  <code>run()</code>, the return value is an instance of the  <code>CompletedProcess</code>  class. As the name suggests,  <code>run()</code>  returns the object only once the child process has ended. It has various attributes that can be helpful, such as the  <code>args</code>  that were used for the process and the  <code>returncode</code>.</p>
<p>To see this clearly, you can assign the result of  <code>run()</code>  to a variable, and then access its attributes such as  <code>.returncode</code>:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; import subprocess</p>
<blockquote>
<blockquote>
<blockquote>
<p>completed_process = subprocess.run([“python”, “<a href="http://timer.py">timer.py</a>”])<br>
usage: <a href="http://timer.py">timer.py</a> [-h] time<br>
<a href="http://timer.py">timer.py</a>: error: the following arguments are required: time</p>
</blockquote>
</blockquote>
</blockquote>
<blockquote>
<blockquote>
<blockquote>
<p>completed_process.returncode<br>
2`</p>
</blockquote>
</blockquote>
</blockquote>
<p>The process has a return code that indicates failure, but it  <strong>doesn’t raise an  <a href="https://realpython.com/python-exceptions/">exception</a></strong>. Typically, when a  <code>subprocess</code>  process fails, you’ll always want an exception to be raised, which you can do by passing in a  <code>check=True</code>  argument:</p>
<p>Python</p>
<p><code>&gt;&gt;&gt; completed_process = subprocess.run( ... ["python", "timer.py"], ... check=True ... ) ... usage: timer.py [-h] time timer.py: error: the following arguments are required: time Traceback (most recent call last): ... subprocess.CalledProcessError: Command '['python', 'timer.py']' returned non-zero exit status 2.</code></p>
<p>There are various ways to deal with failures, some of which will be covered in the next section. The important point to note for now is that  <code>run()</code>  won’t necessarily raise an exception if the process fails unless you’ve passed in a  <code>check=True</code>  argument.</p>
<p>The  <code>CompletedProcess</code>  also has a few attributes relating to  <a href="https://en.wikipedia.org/wiki/Input/output">input/output (I/O)</a>, which you’ll cover in more detail in the  <a href="https://realpython.com/python-subprocess/#communication-with-processes">communicating with processes</a>  section. Before communicating with processes, though, you’ll learn how to handle errors when coding with  <code>subprocess</code>.</p>
<h2 id="subprocess--exceptions"><code>subprocess</code>  Exceptions<a href="https://realpython.com/python-subprocess/#subprocess-exceptions" title="Permanent link"></a></h2>
<p>As you saw earlier, even if a process exits with a return code that represents failure, Python won’t raise an exception. For most use cases of the  <code>subprocess</code>  module, this isn’t ideal. If a process fails, you’ll usually want to handle it somehow, not just carry on.</p>
<p>A lot of  <code>subprocess</code>  use cases involve short personal scripts that you might not spend much time on, or at least  <a href="https://xkcd.com/1319/">shouldn’t spend much time on</a>. If you’re tinkering with a script like this, then you’ll want  <code>subprocess</code>  to fail early and loudly.</p>
<h3 id="calledprocesserror--for-non-zero-exit-code"><code>CalledProcessError</code>  for Non-Zero Exit Code<a href="https://realpython.com/python-subprocess/#calledprocesserror-for-non-zero-exit-code" title="Permanent link"></a></h3>
<p>If a process returns an exit code that isn’t zero, you should interpret that as a failed process. Contrary to what you might expect, the Python  <code>subprocess</code>  module does  <em>not</em>  automatically raise an exception on a non-zero exit code. A failing process is typically not something you want your program to pass over silently, so you can pass a  <code>check=True</code>  argument to  <code>run()</code>  to raise an exception:</p>
<p>Python</p>
<p><code>&gt;&gt;&gt; completed_process = subprocess.run( ... ["python", "timer.py"], ... check=True ... ) ... usage: timer.py [-h] time timer.py: error: the following arguments are required: time Traceback (most recent call last): ... subprocess.CalledProcessError: Command '['python', 'timer.py']' returned non-zero exit status 2.</code></p>
<p>The  <code>CalledProcessError</code>  is raised as soon as the subprocess runs into a non-zero return code. If you’re developing a short personal script, then perhaps this is good enough for you. If you want to handle errors more gracefully, then read on to the section on  <a href="https://realpython.com/python-subprocess/#an-example-of-exception-handling">exception handling</a>.</p>
<p>One thing to bear in mind is that the  <code>CalledProcessError</code>  does not apply to processes that may hang and block your execution indefinitely. To guard against that, you’d want to take advantage of the  <code>timeout</code>  parameter.</p>
<h3 id="timeoutexpired--for-processes-that-take-too-long"><code>TimeoutExpired</code>  for Processes That Take Too Long<a href="https://realpython.com/python-subprocess/#timeoutexpired-for-processes-that-take-too-long" title="Permanent link"></a></h3>
<p>Sometimes processes aren’t well behaved, and they might take too long or just hang indefinitely. To handle those situations, it’s always a good idea to use the  <code>timeout</code>  parameter of the  <code>run()</code>  function.</p>
<p>Passing a  <code>timeout=1</code>  argument to  <code>run()</code>  will cause the function to shut down the process and raise a  <code>TimeoutExpired</code>  error after one second:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; import subprocess</p>
<blockquote>
<blockquote>
<blockquote>
<p>subprocess.run([“python”, “<a href="http://timer.py">timer.py</a>”, “5”], timeout=1)<br>
Starting timer of 5 seconds<br>
.Traceback (most recent call last):<br>
…<br>
subprocess.TimeoutExpired: Command ‘[‘python’, ‘<a href="http://timer.py">timer.py</a>’, ‘5’]’ timed out<br>
after 1.0 seconds`</p>
</blockquote>
</blockquote>
</blockquote>
<p>In this example, the first dot of the timer animation was output, but the subprocess was shut down before being able to complete.</p>
<p>The other type of error that might happen is if the program doesn’t exist on that particular system, which raises one final type of error.</p>
<h3 id="filenotfounderror--for-programs-that-don’t-exist"><code>FileNotFoundError</code>  for Programs That Don’t Exist<a href="https://realpython.com/python-subprocess/#filenotfounderror-for-programs-that-dont-exist" title="Permanent link"></a></h3>
<p>The final type of exception you’ll be looking at is the  <code>FileNotFoundError</code>, which is raised if you try and call a program that doesn’t exist on the target system:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; import subprocess</p>
<blockquote>
<blockquote>
<blockquote>
<p>subprocess.run([“now_you_see_me”])<br>
Traceback (most recent call last):<br>
…<br>
FileNotFoundError: The system cannot find the file specified`</p>
</blockquote>
</blockquote>
</blockquote>
<p>This type of error is raised no matter what, so you don’t need to pass in any arguments for the  <code>FileNotFoundError</code>.</p>
<p>Those are the main exceptions that you’ll run into when using the Python  <code>subprocess</code>  module. For many use cases, knowing the exceptions and making sure that you use  <code>timeout</code>  and  <code>check</code>  arguments will be enough. That’s because if the subprocess fails, then that usually means that your script has failed.</p>
<p>However, if you have a more complex program, then you may want to handle errors more gracefully. For instance, you may need to call many processes over a long period of time. For this, you can use the  <a href="https://realpython.com/python-exceptions/#the-try-and-except-block-handling-exceptions"><code>try</code>  …  <code>except</code></a>  construct.</p>
<h3 id="an-example-of-exception-handling">An Example of Exception Handling<a href="https://realpython.com/python-subprocess/#an-example-of-exception-handling" title="Permanent link"></a></h3>
<p>Here’s a code snippet that shows the main exceptions that you’ll want to handle when using  <code>subprocess</code>:</p>
<pre class=" language-python"><code class="prism  language-python">
`<span class="token keyword">import</span> subprocess

<span class="token keyword">try</span><span class="token punctuation">:</span>
    subprocess<span class="token punctuation">.</span>run<span class="token punctuation">(</span>
        <span class="token punctuation">[</span><span class="token string">"python"</span><span class="token punctuation">,</span> <span class="token string">"timer.py"</span><span class="token punctuation">,</span> <span class="token string">"5"</span><span class="token punctuation">]</span><span class="token punctuation">,</span> timeout<span class="token operator">=</span><span class="token number">10</span><span class="token punctuation">,</span> check<span class="token operator">=</span><span class="token boolean">True</span>
    <span class="token punctuation">)</span>
<span class="token keyword">except</span> FileNotFoundError <span class="token keyword">as</span> exc<span class="token punctuation">:</span>
    <span class="token keyword">print</span><span class="token punctuation">(</span>f<span class="token string">"Process failed because the executable could not be found.\n{exc}"</span><span class="token punctuation">)</span>
<span class="token keyword">except</span> subprocess<span class="token punctuation">.</span>CalledProcessError <span class="token keyword">as</span> exc<span class="token punctuation">:</span>
    <span class="token keyword">print</span><span class="token punctuation">(</span>
        f<span class="token string">"Process failed because did not return a successful return code. "</span>
        f<span class="token string">"Returned {exc.returncode}\n{exc}"</span>
    <span class="token punctuation">)</span>
<span class="token keyword">except</span> subprocess<span class="token punctuation">.</span>TimeoutExpired <span class="token keyword">as</span> exc<span class="token punctuation">:</span>
    <span class="token keyword">print</span><span class="token punctuation">(</span>f<span class="token string">"Process timed out.\n{exc}"</span><span class="token punctuation">)</span>` 
</code></pre>
<p>This snippet shows you an example of how you might handle the three main exceptions raised by the  <code>subprocess</code>  module.</p>
<p>Now that you’ve used  <code>subprocess</code>  in its basic form and handled some exceptions, it’s time to get familiar with what it takes to interact with the shell.</p>
<h2 id="introduction-to-the-shell-and-text-based-programs-with--subprocess">Introduction to the Shell and Text-Based Programs With  <code>subprocess</code><a href="https://realpython.com/python-subprocess/#introduction-to-the-shell-and-text-based-programs-with-subprocess" title="Permanent link"></a></h2>
<p>Some of the most popular use cases of the  <code>subprocess</code>  module are to interact with text-based programs, typically available on the shell. That’s why in this section, you’ll start to explore all the moving parts involved when interacting with text-based programs, and perhaps question if you need the shell at all!</p>
<p>The shell is typically synonymous with the  <a href="https://en.wikipedia.org/wiki/Command-line_interface">command-line interface</a>  or CLI, but this terminology isn’t entirely accurate. There are actually two separate processes that make up the typical command-line experience:</p>
<ol>
<li><strong>The interpreter</strong>, which is typically thought of as the whole CLI. Common interpreters are Bash on Linux, Zsh on macOS, or PowerShell on Windows. In this tutorial, the interpreter will be referred to as the shell.</li>
<li><strong>The interface</strong>, which displays the output of the interpreter in a window and sends user keystrokes to the interpreter. The interface is a separate process from the shell, sometimes called a  <a href="https://en.wikipedia.org/wiki/Terminal_emulator">terminal emulator</a>.</li>
</ol>
<p>When on the command line, it’s common to think that you’re interacting directly with the shell, but you’re really interacting with the  <em>interface</em>. The interface takes care of sending your commands to the shell and displaying the shell’s output back to you.</p>
<p>With this important distinction in mind, it’s time to turn your attention to what  <code>run()</code>  is actually doing. It’s common to think that calling  <code>run()</code>  is somehow the same as typing a command in a terminal interface, but there are important differences.</p>
<p>While all new process are created with the same  <a href="https://en.wikipedia.org/wiki/System_call">system calls</a>, the context from which the system call is made is different. The  <code>run()</code>  function can make a system call directly and doesn’t need to go through the shell to do so:</p>
<p>In fact, many programs that are thought of as shell programs, such as  <a href="https://git-scm.com/">Git</a>, are really just  <em>text-based</em>  programs that don’t need a shell to run. This is especially true of UNIX environments, where all of the familiar utilities like  <code>ls</code>,  <code>rm</code>,  <code>grep</code>, and  <code>cat</code>  are actually separate executables that can be called directly:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; # Linux or macOS</p>
<blockquote>
<blockquote>
<blockquote>
<p>import subprocess<br>
subprocess.run([“ls”])<br>
<a href="http://timer.py">timer.py</a><br>
CompletedProcess(args=[‘ls’], returncode=0)`</p>
</blockquote>
</blockquote>
</blockquote>
<p>There are some tools that are specific to shells, though. Finding tools embedded within the shell is far more common on Windows shells like PowerShell, where commands like  <code>ls</code>  are  <em>part of the shell itself</em>  and not separate executables like they are in a UNIX environment:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; # Windows</p>
<blockquote>
<blockquote>
<blockquote>
<p>import subprocess<br>
subprocess.run([“ls”])<br>
Traceback (most recent call last):<br>
…<br>
FileNotFoundError: [WinError 2] The system cannot find the file specified`</p>
</blockquote>
</blockquote>
</blockquote>
<p>In PowerShell,  <code>ls</code>  is the default alias for  <code>Get-ChildItem</code>, but calling that won’t work either because  <code>Get-ChildItem</code>  isn’t a separate executable—it’s  <em>part of PowerShell</em>  itself.</p>
<p>The fact that many text-based programs can operate independently from the shell may make you wonder if you can cut out the middle process—namely, the shell—and use  <code>subprocess</code>  directly with the text-based programs typically associated with the shell.</p>
<h3 id="use-cases-for-the-shell-and--subprocess">Use Cases for the Shell and  <code>subprocess</code><a href="https://realpython.com/python-subprocess/#use-cases-for-the-shell-and-subprocess" title="Permanent link"></a></h3>
<p>There are a few common reasons why you might want to call the shell with the  <code>Python</code>  subprocess module:</p>
<ul>
<li>When you know certain commands are only available via the shell, which is more common in Windows</li>
<li>When you’re experienced in writing shell scripts with a particular shell, so you want to leverage your ability there to do certain tasks while still working primarily in Python</li>
<li>When you’ve inherited a large shell script that might do nothing that Python couldn’t do, but would take a long time to reimplement in Python</li>
</ul>
<p>This isn’t an exhaustive list!</p>
<p>You might use the shell to wrap programs or to do some text processing. However, the syntax can be very cryptic when compared to Python. With Python, text processing workflows are easier to write, easier to maintain,  <a href="https://stackoverflow.com/a/4493209/10445017">generally more performant</a>, and cross-platform to boot. So it’s well worth considering going without the shell.</p>
<p>What often happens, though, is that you just don’t have the time or it’s not worth the effort to reimplement existing shell scripts in Python. In those cases, using  <code>subprocess</code>  for some  <a href="https://www.youtube.com/watch?v=Jd8ulMb6_ls">sloppy Python</a>  isn’t a bad thing!</p>
<p>Common reasons for using  <code>subprocess</code>  itself are similar in nature to using the shell with  <code>subprocess</code>:</p>
<ul>
<li>When you have to use or analyze a  <a href="https://en.wikipedia.org/wiki/Black_box">black box</a>, or even a  <a href="https://en.wikipedia.org/wiki/White_box_(software_engineering)">white box</a></li>
<li>When you want a wrapper for an application</li>
<li>When you need to launch another application</li>
<li>As an alternative to basic shell scripts</li>
</ul>
<p><strong>Note:</strong>  A  <a href="https://en.wikipedia.org/wiki/Black_box">black box</a>  could be a program that can be freely used but whose source code isn’t available, so there’s no way to know exactly what it does and no way to modify its internals.</p>
<p>Similarly, a  <a href="https://en.wikipedia.org/wiki/White_box_(software_engineering)">white box</a>  could be a program whose source code is available but can’t be changed. It could also be a program whose source code you could change, but its complexity means that it would take you a long time to get your head around it to be able to change it.</p>
<p>In these cases, you can use  <code>subprocess</code>  to wrap your boxes of varying opacity, bypassing any need to change or reimplement things in Python.</p>
<p>Often you’ll find that for  <code>subprocess</code>  use cases, there will be a dedicated library for that task. Later in the tutorial, you’ll examine a  <a href="https://realpython.com/python-subprocess/#creating-a-new-project-an-example">script that creates a Python project</a>, complete with a  <a href="https://realpython.com/python-virtual-environments-a-primer/">virtual environment</a>  and a fully initialized  <a href="https://realpython.com/python-git-github-intro/">Git</a>  repository. However, the  <a href="https://github.com/cookiecutter/cookiecutter">Cookiecutter</a>  and  <a href="https://copier.readthedocs.io/">Copier</a>  libraries already exist for that purpose.</p>
<p>Even though specific libraries might be able to do your task, it may still be worth doing things with  <code>subprocess</code>. For one, it might be much faster for you to execute what you already know how to do, rather than learning a new library.</p>
<p>Additionally, if you’re sharing this script with friends or colleagues, it’s convenient if your script is pure Python without any other dependencies, especially if your script needs to go on minimal environments like servers or embedded systems.</p>
<p>However, if you’re using  <code>subprocess</code>  instead of  <code>pathlib</code>  to read and write a few files with Bash, you might want to consider learning how to  <a href="https://realpython.com/read-write-files-python/">read and write</a>  with Python. Learning how to read and write files doesn’t take long, and it’ll definitely be worth it for such a common task.</p>
<p>With that out of the way, it’s time to get familiar with the shell environments on both Windows and UNIX-based systems.</p>
<h3 id="basic-usage-of--subprocess--with-unix-based-shells">Basic Usage of  <code>subprocess</code>  With UNIX-Based Shells<a href="https://realpython.com/python-subprocess/#basic-usage-of-subprocess-with-unix-based-shells" title="Permanent link"></a></h3>
<p>To run a shell command using  <code>run()</code>, the  <code>args</code>  should contain the shell that you want to use, the flag to indicate that you want it to run a specific command, and the command that you’re passing in:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; import subprocess</p>
<blockquote>
<blockquote>
<blockquote>
<p>subprocess.run([“bash”, “-c”, “ls /usr/bin | grep pycode”])<br>
pycodestyle<br>
pycodestyle-3<br>
pycodestyle-3.10<br>
CompletedProcess(args=[‘bash’, ‘-c’, ‘ls /usr/bin | grep pycode’], returncode=0)`</p>
</blockquote>
</blockquote>
</blockquote>
<p>Here a common shell command is demonstrated. It uses  <code>ls</code>  piped into  <code>grep</code>  to filter some of the entries. The shell is handy for this kind of operation because you can take advantage of the pipe operator (<code>|</code>). You’ll cover pipes in more detail  <a href="https://realpython.com/python-subprocess/#pipes-and-the-shell">later</a>.</p>
<p>You can replace  <code>bash</code>  with the shell of your choice. The  <code>-c</code>  flag stands for  <em>command</em>, but may be different depending on the shell that you’re using. This is almost the exact equivalent of what happens when you add the  <code>shell=True</code>  argument:</p>
<p>Python</p>
<p><code>&gt;&gt;&gt; subprocess.run(["ls /usr/bin | grep pycode"], shell=True) pycodestyle pycodestyle-3 pycodestyle-3.10 CompletedProcess(args=['ls /usr/bin | grep pycode'], returncode=0)</code></p>
<p>The  <code>shell=True</code>  argument uses  <code>["sh", "-c", ...]</code>  behind the scenes, so it’s almost the equivalent of the previous example.</p>
<p><strong>Note:</strong>  On UNIX-based systems, the  <code>sh</code>  shell was traditionally the  <a href="https://en.wikipedia.org/wiki/Bourne_shell">Bourne shell</a>. That said, the Bourne shell is now quite old, so many operating systems use  <code>sh</code>  as a link to  <a href="https://www.gnu.org/software/bash/">Bash</a>  or  <a href="https://en.wikipedia.org/wiki/Almquist_shell#dash">Dash</a>.</p>
<p>This can often be different from the shell used with the terminal interface that you interact with. For instance, since macOS Catalina, the default shell that you’ll find on the command-line app has changed from Bash to  <a href="https://www.zsh.org/">Zsh</a>, yet  <code>sh</code>  often still points to Bash. Likewise, on Ubuntu,  <code>sh</code>  points to Dash, but the default that you typically interact with on the command-line application is still Bash.</p>
<p>So, calling  <code>sh</code>  on your system may result in a different shell than what is found in this tutorial. Nevertheless, the examples should all still work.</p>
<p>You’ll note that the token after  <code>"-c"</code>  should be one single token, with all the spaces included. Here you’re giving control to the shell to parse the command. If you were to include more tokens, this would be interpreted as more options to pass to the shell executable, not as additional commands to run inside the shell.</p>
<h3 id="a-security-warning">A Security Warning<a href="https://realpython.com/python-subprocess/#a-security-warning" title="Permanent link"></a></h3>
<p>If at any point you plan to get user input and somehow translate that to a call to  <code>subprocess</code>, then you have to be very careful of  <a href="https://en.wikipedia.org/wiki/Code_injection">injection</a>  attacks. That is, take into account potential malicious actors. There are many ways to cause havoc if you just let people run code on your machine.</p>
<p>To use a very simplistic example, where you take user input and send it, unfiltered, to subprocess to run on the shell:</p>
<pre><code>-   [Windows](https://realpython.com/python-subprocess/#windows-3)
-   [Linux + macOS](https://realpython.com/python-subprocess/#linux-macos-3)

Python

`# unsafe_program.py

import subprocess

# ...

subprocess.run(["bash", "-c", f"ls {input()}"])

# ...` 
</code></pre>
<p>You can imagine the intended use case is to wrap  <code>ls</code>  and add something to it. So the expected user behavior is to provide a path like  <code>"/home/realpython/"</code>. However, if a malicious actor realized what was happening, they could execute almost any code they wanted. Take the following, for instance, but  <strong>be careful with this</strong>:</p>
<blockquote>
<p><code>/home/realpython/; echo 'You could've been hacked: rm -rf /*'</code></p>
</blockquote>
<p>Again,  <strong>beware</strong>! These innocent-looking lines could try and delete everything on the system! In this case the malicious part is in quotes, so it won’t run, but if the quotes were not there, you’d be in trouble. The key part that does this is the call to  <code>rm</code>  with the relevant flags to recursively delete all files, folders, and subfolders, and it’ll work to force the deletion through. It can run the  <code>echo</code>  and potentially the  <code>rm</code>  as entirely separate commands by adding semicolons, which act as command separators allowing what would usually be multiple lines of code to run on one line.</p>
<p>Running these malicious commands would cause irreparable damage to the file system, and would require reinstalling the operating system. So, beware!</p>
<p>Luckily, the operating system wouldn’t let you do this to some particularly important files. The  <code>rm</code>  command would need to use  <a href="https://en.wikipedia.org/wiki/Sudo"><code>sudo</code></a>  in UNIX-based systems, or be run as an administrator in Windows to be completely successful in its mayhem. The command would probably delete a lot of important stuff before stopping, though.</p>
<p>So, make sure that if you’re dynamically building user inputs to feed into a  <code>subprocess</code>  call, then you’re very careful! With that warning, coming up you’ll be covering using the outputs of commands and chaining commands together—in short, how to communicate with processes once they’ve started.</p>
<h2 id="communication-with-processes">Communication With Processes</h2>
<p>You’ve used the  <code>subprocess</code>  module to execute programs and send basic commands to the shell. But something important is still missing. For many tasks that you might want to use  <code>subprocess</code>  for, you might want to dynamically send inputs or use the outputs in your Python code later.</p>
<p>To communicate with your process, you first should understand a little bit about how processes communicate in general, and then you’ll take a look at two examples to come to grips with the concepts.</p>
<h3 id="the-standard-io-streams">The Standard I/O Streams<a href="https://realpython.com/python-subprocess/#the-standard-io-streams" title="Permanent link"></a></h3>
<p>A  <a href="https://en.wikipedia.org/wiki/Stream_(computing)">stream</a>  at its most basic represents a sequence of elements that aren’t available all at once. When you  <a href="https://realpython.com/working-with-files-in-python/">read characters and lines from a file</a>, you’re working with a stream in the form of a file object, which at its most basic is a  <a href="https://realpython.com/why-close-file-python/#in-short-files-are-resources-limited-by-the-operating-system">file descriptor</a>. File descriptors are often used for streams. So, it’s not uncommon to see the terms  <em>stream</em>,  <em>file</em>, and  <em>file-like</em>  used interchangeably.</p>
<p>When processes are initialized, there are three special streams that a process makes use of. A process does the following:</p>
<ol>
<li>Reads  <code>stdin</code>  for input</li>
<li>Writes to  <code>stdout</code>  for general output</li>
<li>Writes to  <code>stderr</code>  for error reporting</li>
</ol>
<p>These are the  <a href="https://en.wikipedia.org/wiki/Standard_streams">standard streams</a>—a cross-platform pattern for process communication.</p>
<p>Sometimes the child process inherits these streams from the parent. This is what’s happening when you use  <code>subprocess.run()</code>  in the REPL and are able to see the output of the command. The  <code>stdout</code>  of the Python interpreter is inherited by the subprocess.</p>
<p>When you’re in a REPL environment, you’re looking at a command-line interface process, complete with the three standard I/O streams. The interface has a shell process as a child process, which itself has a Python REPL as a child. In this situation, unless you specify otherwise,  <code>stdin</code>  comes from the keyboard, while  <code>stdout</code>  and  <code>stderr</code>  are displayed on-screen. The interface, the shell, and the REPL share the streams:</p>
<p><a href="https://files.realpython.com/media/2022-05-31_17_26_47-process__Figma.f98ed0f101b2.png"><img src="https://files.realpython.com/media/2022-05-31_17_26_47-process__Figma.f98ed0f101b2.png" alt="Diagram demonstrating the structure of processes involved in repl environment"></a></p>
<p>You can think of the standard I/O streams as byte dispensers. The subprocess fills up  <code>stdout</code>  and  <code>stderr</code>, and you fill up  <code>stdin</code>. Then you read the bytes in  <code>stdout</code>  and  <code>stderr</code>, and the subprocess reads from  <code>stdin</code>.</p>
<p>As with a dispenser, you can stock  <code>stdin</code>  before it gets linked up to a child process. The child process will then read from  <code>stdin</code>  as and when it needs to. Once a process has read from a stream, though, the bytes are dispensed. You can’t go back and read them again:</p>
<p>These three streams, or files, are the basis for communicating with your process. In the next section, you’ll start to see this in action by getting the output of a magic number generator program.</p>
<h3 id="the-magic-number-generator-example">The Magic Number Generator Example<a href="https://realpython.com/python-subprocess/#the-magic-number-generator-example" title="Permanent link"></a></h3>
<p>Often, when using the  <code>subprocess</code>  module, you’ll want to use the output for something and not just display the output as you have been doing so far. In this section, you’ll use a magic number generator that outputs, well, a magic number.</p>
<p>Imagine that the magic number generator is some obscure program, a black box, inherited across generations of  <a href="https://xkcd.com/705/">sysadmins</a>  at your job. It outputs a magic number that you need for your secret calculations. You’ll read from the  <code>stdout</code>  of  <code>subprocess</code>  and use it in your wrapper Python program:</p>
<p>Python</p>
<p>`# magic_number.py</p>
<p>from random import randint</p>
<p>print(randint(0, 1000))`</p>
<p>Okay, not really so magical. That said, it’s not the magic number generator that you’re interested in—it’s interacting with a hypothetical black box with  <code>subprocess</code>  that’s interesting. To grab the number generator’s output to use later, you can pass in a  <code>capture_output=True</code>  argument to  <code>run()</code>:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; import subprocess</p>
<blockquote>
<blockquote>
<blockquote>
<p>magic_number_process = subprocess.run(<br>
…     [“python”, “magic_number.py”], capture_output=True<br>
… )</p>
</blockquote>
</blockquote>
<blockquote>
<blockquote>
<p>magic_number_process.stdout<br>
b’769\n’`</p>
</blockquote>
</blockquote>
</blockquote>
<p>Passing a  <code>capture_output</code>  argument of  <code>True</code>  to  <code>run()</code>  makes the output of the process available at the  <code>.stdout</code>  attribute of the completed process object. You’ll note that it’s returned as a  <a href="https://docs.python.org/3/library/stdtypes.html#bytes-objects">bytes object</a>, so you need to be mindful of  <a href="https://realpython.com/python-subprocess/#the-decoding-of-standard-streams">encodings</a>  when reading it.</p>
<p>Also note that the  <code>.stdout</code>  attribute of the  <code>CompletedProcess</code>  is no longer a stream. The stream has been read, and it’s stored as a bytes object in the  <code>.stdout</code>  attribute.</p>
<p>With the output available, you can use more than one subprocess to grab values and operate on them in your code:</p>
<pre><code>Python

`&gt;&gt;&gt; import subprocess
&gt;&gt;&gt; sum(
...     int(
...         subprocess.run(
...             ["python", "magic_number.py"], capture_output=True
...         ).stdout
...     )
...     for _ in range(2)
... )
1085` 
</code></pre>
<p>In this example, you start two magic number processes that fetch two magic numbers and then add them together. For now, you rely on the automatic decoding of the bytes object by the  <code>int()</code>  constructor. In the next section, though, you’ll learn how to decode and encode explicitly.</p>
<h3 id="the-decoding-of-standard-streams">The Decoding of Standard Streams<a href="https://realpython.com/python-subprocess/#the-decoding-of-standard-streams" title="Permanent link"></a></h3>
<p>Processes communicate in bytes, and you have a few different ways to deal with  <a href="https://realpython.com/python-encodings-guide/">encoding and decoding</a>  these bytes. Beneath the surface,  <code>subprocess</code>  has a few ways of getting into  <a href="https://github.com/python/cpython/blob/3.10/Lib/subprocess.py#L849"><em>text mode</em></a>.</p>
<p><em>Text mode</em>  means that  <code>subprocess</code>  will try to take care of encoding itself. To do that, it needs to know what character encoding to use. Most of the options for doing this in  <code>subprocess</code>  will try to use the default encoding. However, you generally  <a href="https://peps.python.org/pep-0597/#using-the-default-encoding-is-a-common-mistake">want to be explicit about what encoding to use</a>  to prevent a bug that would be hard to find in the future.</p>
<p>You can pass a  <code>text=True</code>  argument for Python to take care of encodings using the default encoding. But, as mentioned, it’s always safer to specify the encodings explicitly using the  <code>encoding</code>  argument, as not all systems work with the  <em>nearly</em>  universal  <a href="https://en.wikipedia.org/wiki/UTF-8">UTF-8</a>:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; magic_number_process = subprocess.run(<br>
…     [“python”, “magic_number.py”], capture_output=True, encoding=“utf-8”<br>
… )<br>
…</p>
<blockquote>
<blockquote>
<blockquote>
<p>magic_number_process.stdout<br>
‘647\n’`</p>
</blockquote>
</blockquote>
</blockquote>
<p>If in  <em>text mode</em>, the  <code>.stdout</code>  attribute on a  <code>CompletedProcess</code>  is now a string and not a bytes object.</p>
<p>You can also decode the bytes returned by calling the  <code>.decode()</code>  method on the  <code>stdout</code>  attribute directly, without requiring  <em>text mode</em>  at all:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; magic_number_process = subprocess.run(<br>
…     [“python”, “magic_number.py”], capture_output=True<br>
… )<br>
…</p>
<blockquote>
<blockquote>
<blockquote>
<p>magic_number_process.stdout.decode(“utf-8”)<br>
‘72\n’`</p>
</blockquote>
</blockquote>
</blockquote>
<p>There are other ways to put  <code>run()</code>  into  <em>text mode</em>. You can also set a  <code>True</code>  value for  <code>errors</code>  or  <code>universal_newlines</code>, which will also put  <code>run()</code>  into  <em>text mode</em>. This may seem redundant, but much of this is kept for backwards compatibility, seeing as the  <code>subprocess</code>  module has changed over the years.</p>
<p>Now that you know how to read and decode the output of a process, it’s time to take a look at writing to the input of a process.</p>
<h3 id="reaction-game-example">Reaction Game Example<a href="https://realpython.com/python-subprocess/#reaction-game-example" title="Permanent link"></a></h3>
<p>In this section, you’ll use  <code>subprocess</code>  to interact with a command-line game. It’s a basic program that’s designed to test a human’s reaction time. With your knowledge of standard I/O streams, though, you’ll be able to hack it! The source code of the game makes use of the  <a href="https://realpython.com/python-time-module/"><code>time</code></a>  and  <a href="https://realpython.com/python-random/"><code>random</code></a>  module:</p>
<p>Python</p>
<p>`# reaction_game.py</p>
<p>from time import perf_counter, sleep<br>
from random import random</p>
<p>print(“Press enter to play”)<br>
input()<br>
print(“Ok, get ready!”)<br>
sleep(random() * 5 + 1)<br>
print(“go!”)<br>
start = perf_counter()<br>
input()<br>
end = perf_counter()<br>
print(f"You reacted in {(end  -  start)  *  1000:.0f} milliseconds!\nGoodbye!")`</p>
<p>The program starts, asks for the user to press enter, and then after a random amount of time will ask the user to press enter again. It  <a href="https://realpython.com/python-timer/">measures</a>  from the time the message appears to the time the user presses enter, or at least that’s what the game developer thinks:</p>
<p>The  <code>input()</code>  function will read from  <code>stdin</code>  until it reaches a newline, which means an  Enter  keystroke in this context. It returns everything it consumed from  <code>stdin</code>  except the newline. With that knowledge, you can use  <code>subprocess</code>  to interact with this game:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; import subprocess</p>
<blockquote>
<blockquote>
<blockquote>
<p>process = subprocess.run(<br>
…     [“python”, “reaction_game.py”], input="\n\n", encoding=“utf-8”<br>
… )<br>
…<br>
Press enter to play<br>
Ok, get ready!<br>
go!<br>
You reacted in 0 milliseconds!<br>
Goodbye!`</p>
</blockquote>
</blockquote>
</blockquote>
<p>A reaction time of 0 milliseconds! Not bad! Considering the  <a href="https://humanbenchmark.com/tests/reactiontime/statistics">average human reaction time</a>  is around 270 milliseconds, your program is definitely superhuman. Note that the game rounds its output, so 0 milliseconds doesn’t mean it’s instantaneous.</p>
<p>The  <code>input</code>  argument passed to  <code>run()</code>  is a string consisting of two newlines. The  <code>encoding</code>  parameter is set to  <code>utf-8</code>, which puts  <code>run()</code>  into  <em>text mode</em>. This sets up the process for it to receive the input you that give it.</p>
<p>Before the program starts,  <code>stdin</code>  is stocked, waiting for the program to consume the newlines it contains. One newline is consumed to start the game, and the next newline is consumed to react to  <code>go!</code>.</p>
<p>Now that you know what’s happening—namely that  <code>stdin</code>  can be  <em>stocked</em>, as it were—you can hack the program yourself without  <code>subprocess</code>. If you start the game and then press  Enter  a few times, that’ll stock up  <code>stdin</code>  with a few newlines that the program will automatically consume once it gets to the  <code>input()</code>  line. So your reaction time is really only the time it takes for the reaction game to execute  <code>start = time()</code>  and consume an input:</p>
<p>The game developer gets wise to this, though, and vows to release another version, which will guard against this exploit. In the meantime, you’ll peek a bit further under the hood of  <code>subprocess</code>  and learn about how it wires up the standard I/O streams.</p>
<h2 id="pipes-and-the-shell">Pipes and the Shell<a href="https://realpython.com/python-subprocess/#pipes-and-the-shell" title="Permanent link"></a></h2>
<p>To really understand subprocesses and the redirection of streams, you really need to understand pipes and what they are. This is especially true if you want to wire up two processes together, feeding one  <code>stdout</code>  into another process’s  <code>stdin</code>, for instance. In this section, you’ll be coming to grips with pipes and how to use them with the  <code>subprocess</code>  module.</p>
<h3 id="introduction-to-pipes">Introduction to Pipes<a href="https://realpython.com/python-subprocess/#introduction-to-pipes" title="Permanent link"></a></h3>
<p>A pipe, or  <a href="https://en.wikipedia.org/wiki/Pipeline_(computing)">pipeline</a>, is a special stream that, instead of having one file handle as most files do, has two. One handle is read-only, and the other is write-only. The name is very descriptive—a pipe serves to pipe a byte stream from one process to another. It’s also buffered, so a process can write to it, and it’ll hold onto those bytes until it’s read, like a dispenser.</p>
<p>You may be used to seeing pipes on the command line, as you did in the  <a href="https://realpython.com/python-subprocess/#introduction-to-the-shell-and-text-based-programs-with-subprocess">section on shells</a>:</p>
<p>Shell</p>
<p><code>$ ls /usr/bin | grep python</code></p>
<p>This command tells the shell to create an  <code>ls</code>  process to list all the files in  <code>/usr/bin</code>. The pipe operator (<code>|</code>) tells the shell to create a pipe from the  <code>stdout</code>  of the  <code>ls</code>  process and feed it into the  <code>stdin</code>  of the  <code>grep</code>  process. The  <code>grep</code>  process filters out all the lines that don’t contain the string  <code>python</code>.</p>
<p>Windows doesn’t have  <code>grep</code>, but a rough equivalent of the same command would be as follows:</p>
<p>Windows PowerShell</p>
<p><code>PS&gt; ls "C:\Program Files" | Out-String -stream | Select-String windows</code></p>
<p>However, on Windows PowerShell, things work very differently. As you learned in the  <a href="https://realpython.com/python-subprocess/#basic-usage-of-subprocess-with-windows-shells">Windows shell section</a>  of this tutorial, the different commands are not separate executables. Therefore, PowerShell is internally redirecting the output of one command into another without starting new processes.</p>
<p><strong>Note:</strong>  If you don’t have access to a UNIX-based operating system but have Windows 10 or above, then you actually  <em>do</em>  have access to a UNIX-based operating system! Check out  <a href="https://docs.microsoft.com/en-us/windows/wsl/install">Windows Subsystem for Linux</a>, which will give you access to a fully featured Linux shell.</p>
<p>You can use pipes for different processes on PowerShell, though getting into the intricacies of which ones is outside the scope of this tutorial. For more information on PowerShell pipes, check out the  <a href="https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_pipelines">documentation</a>. So, for the rest of the pipe examples, only UNIX-based examples will be used, as the basic mechanism is the same for both systems. They’re not nearly as common on Windows, anyway.</p>
<p>If you want to let the shell take care of piping processes into one another, then you can just pass the whole string as a command into  <code>subprocess</code>:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; import subprocess</p>
<blockquote>
<blockquote>
<blockquote>
<p>subprocess.run([“sh” , “-c”, “ls /usr/bin | grep python”])<br>
python3<br>
python3-config<br>
python3.8<br>
python3.8-config<br>
…<br>
CompletedProcess(…)`</p>
</blockquote>
</blockquote>
</blockquote>
<p>This way, you can let your chosen shell take care of piping one process into another, instead of trying to reimplement things in Python. This is a perfectly valid choice in certain situations.</p>
<p><a href="https://realpython.com/python-subprocess/#pipe-simulation-with-run">Later in the tutorial</a>, you’ll also come to see that you  <em>can’t</em>  pipe processes directly with  <code>run()</code>. For that, you’ll need the more complicated  <code>Popen()</code>. Actual piping is demonstrated in  <a href="https://realpython.com/python-subprocess/#connecting-two-processes-together-with-pipes">Connecting Two Porcesses Together With Pipes</a>, near the end of the tutorial.</p>
<p>Whether you mean to pipe one process into another with the  <code>subprocess</code>  module or not, the  <code>subprocess</code>  module makes extensive use of pipes behind the scenes.</p>
<h3 id="the-pipes-of--subprocess">The Pipes of  <code>subprocess</code><a href="https://realpython.com/python-subprocess/#the-pipes-of-subprocess" title="Permanent link"></a></h3>
<p>The Python  <code>subprocess</code>  module uses pipes extensively to interact with the processes that it starts. In a previous example, you used the  <code>capture_output</code>  parameter to be able to access  <code>stdout</code>:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; import subprocess</p>
<blockquote>
<blockquote>
<blockquote>
<p>magic_number_process = subprocess.run(<br>
…     [“python”, “magic_number.py”], capture_output=True<br>
… )</p>
</blockquote>
</blockquote>
<blockquote>
<blockquote>
<p>magic_number_process.stdout<br>
b’769\n’`</p>
</blockquote>
</blockquote>
</blockquote>
<p><code>capture_output=True</code>  is equivalent to explicitly setting the  <code>stdout</code>  and  <code>stderr</code>  parameters to the  <code>subprocess.PIPE</code>  constant:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; import subprocess</p>
<blockquote>
<blockquote>
<blockquote>
<p>magic_number_process = subprocess.run(<br>
…     [“python”, “magic_number.py”],<br>
…     stdout=subprocess.PIPE,<br>
…     stderr=subprocess.PIPE<br>
… )<br>
…</p>
</blockquote>
</blockquote>
<blockquote>
<blockquote>
<p>magic_number_process.stdout<br>
b’769\n’`</p>
</blockquote>
</blockquote>
</blockquote>
<p>The  <code>PIPE</code>  constant is nothing special. It’s just a number that indicates to  <code>subprocess</code>  that a pipe should be created. The function then creates a pipe to link up to the  <code>stdout</code>  of the subprocess, which the function then reads into the  <code>CompletedProcess</code>  object’s  <code>stdout</code>  attribute. By the time it’s a  <code>CompletedProcess</code>, it’s no longer a pipe, but a bytes object that can be accessed multiple times.</p>
<p><strong>Note:</strong>  Pipe buffers have a limited capacity. Depending on the system you are running on, you may easily run into that limit if you plan on holding large quantities of data in the buffer. To work around this limit, you can use normal files.</p>
<p>You can also pass a  <a href="https://realpython.com/working-with-files-in-python/#pythons-with-open-as-pattern">file object</a>  to any of the standard stream parameters:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; from tempfile import TemporaryFile</p>
<blockquote>
<blockquote>
<blockquote>
<p>with TemporaryFile() as f:<br>
…     ls_process = subprocess.run([“python”, “magic_number.py”], stdout=f)<br>
…     f.seek(0)<br>
…     print(f.read().decode(“utf-8”))<br>
…<br>
0<br>
554`</p>
</blockquote>
</blockquote>
</blockquote>
<p>You  <em>can’t</em>  pass a bytes object or a string directly to the  <code>stdin</code>  argument, though. It needs to be something file-like.</p>
<p>Note that the  <code>0</code>  that gets returned first is from the call to  <a href="https://docs.python.org/3/library/io.html?highlight=seek#io.IOBase.seek"><code>seek()</code></a>  which returns the new stream position, which in this case is the start of the stream.</p>
<p>The  <code>input</code>  parameter is similar to the  <code>capture_output</code>  parameter in that it’s a shortcut. Using the  <code>input</code>  parameter will create a buffer to store the contents of  <code>input</code>, and then link the file up to the new process to serve as its  <code>stdin</code>.</p>
<p>To actually link up two processes with a pipe from within  <code>subprocess</code>  is something that you  <em>can’t</em>  do with  <code>run()</code>. Instead, you can delegate the plumbing to the shell, as you did earlier in the  <a href="https://realpython.com/python-subprocess/#introduction-to-the-shell-and-text-based-programs-with-subprocess">Introduction to the Shell and Text Based Programs with  <code>subprocess</code></a>  section.</p>
<p>If you needed to link up different processes without delegating any of the work to the shell, then you  <a href="https://realpython.com/python-subprocess/#connecting-two-processes-together-with-pipes">could do that with the underlying  <code>Popen()</code>  constructor</a>. You’ll cover  <code>Popen()</code>  in a later  <a href="https://realpython.com/python-subprocess/#the-popen-class">section</a>. In the next section, though, you’ll be  <em>simulating</em>  a pipe with  <code>run()</code>  because in most cases, it’s not vital for processes to be linked up directly.</p>
<h3 id="pipe-simulation-with--run">Pipe Simulation With  <code>run()</code><a href="https://realpython.com/python-subprocess/#pipe-simulation-with-run" title="Permanent link"></a></h3>
<p>Though you can’t actually link up two processes together with a pipe by using the  <code>run()</code>  function, at least not without delegating it to the shell, you can simulate piping by judicious use of the  <code>stdout</code>  attribute.</p>
<p>If you’re on a UNIX-based system where almost all typical shell commands are separate executables, then you can just set the  <code>input</code>  of the second process to the  <code>.stdout</code>  attribute of the first  <code>CompletedProcess</code>:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; import subprocess</p>
<blockquote>
<blockquote>
<blockquote>
<p>ls_process = subprocess.run([“ls”, “/usr/bin”], stdout=subprocess.PIPE)<br>
grep_process = subprocess.run(<br>
…     [“grep”, “python”], input=ls_process.stdout, stdout=subprocess.PIPE<br>
… )</p>
</blockquote>
</blockquote>
<blockquote>
<blockquote>
<p>print(grep_process.stdout.decode(“utf-8”))<br>
python3<br>
python3-config<br>
python3.8<br>
python3.8-config<br>
…`</p>
</blockquote>
</blockquote>
</blockquote>
<p>Here the  <code>.stdout</code>  attribute of the  <code>CompletedProcess</code>  object of  <code>ls</code>  is set to the  <code>input</code>  of the  <code>grep_process</code>. It’s important that it’s set to  <code>input</code>  rather than  <code>stdin</code>. This is because the  <code>.stdout</code>  attribute isn’t a file-like object. It’s a bytes object, so it can’t be used as an argument to  <code>stdin</code>.</p>
<p>As an alternative, you can operate directly with files too, setting them to the standard stream parameters. When using files, you set the file object as the argument to  <code>stdin</code>, instead of using the  <code>input</code>  parameter:</p>
<p>Python</p>
<p>`&gt;&gt;&gt; import subprocess</p>
<blockquote>
<blockquote>
<blockquote>
<p>from tempfile import TemporaryFile<br>
with TemporaryFile() as f:<br>
…     ls_process = subprocess.run([“ls”, “/usr/bin”], stdout=f)<br>
…     f.seek(0)<br>
…     grep_process = subprocess.run(<br>
…         [“grep”, “python”], stdin=f, stdout=subprocess.PIPE<br>
…     )<br>
…<br>
0 # from f.seek(0)</p>
</blockquote>
</blockquote>
<blockquote>
<blockquote>
<p>print(grep_process.stdout.decode(“utf-8”))<br>
python3<br>
python3-config<br>
python3.8<br>
python3.8-config<br>
…`</p>
</blockquote>
</blockquote>
</blockquote>
<p>As you learned in the previous section, for Windows PowerShell, doing something like this doesn’t make a whole lot of sense because most of the time, these utilities are part of PowerShell itself. Because you aren’t dealing with separate executables, piping becomes less of a necessity. However, the pattern for piping is still the same if something like this needs to be done.</p>
<p>With most of the tools out the way, it’s now time to think about some practical applications for  <code>subprocess</code>.</p>
<h2 id="practical-ideas">Practical Ideas<a href="https://realpython.com/python-subprocess/#practical-ideas" title="Permanent link"></a></h2>
<p>When you have an issue that you want to solve with Python, sometimes the  <code>subprocess</code>  module is the easiest way to go, even though it may not be the most correct.</p>
<p>Using  <code>subprocess</code>  is often tricky to get working across different platforms, and it has inherent  <a href="https://realpython.com/python-subprocess/#a-security-warning">dangers</a>. But even though it may involve some  <a href="https://www.youtube.com/watch?v=Jd8ulMb6_ls">sloppy Python</a>, using  <code>subprocess</code>  can be a very quick and efficient way to solve a problem.</p>
<p>As mentioned, for most tasks you can imagine doing with  <code>subprocess</code>, there’s usually a library out there that’s dedicated to that specific task. The library will almost certainly use  <code>subprocess</code>, and the developers will have worked hard to make the code reliable and to cover all the corner cases that can make using  <code>subprocess</code>  difficult.</p>
<p>So, even though dedicated libraries exist, it can often be simpler to just use  <code>subprocess</code>, especially if you’re in an environment where you need to limit your dependencies.</p>
<p>In the following sections, you’ll be exploring a couple of practical ideas.</p>
<h3 id="creating-a-new-project-an-example">Creating a New Project: An Example<a href="https://realpython.com/python-subprocess/#creating-a-new-project-an-example" title="Permanent link"></a></h3>
<p>Say you often need to create new local projects, each complete with a  <a href="https://realpython.com/python-virtual-environments-a-primer/">virtual environment</a>  and initialized as a  <a href="https://realpython.com/python-git-github-intro/">Git repository</a>. You could reach for the  <a href="https://github.com/cookiecutter/cookiecutter">Cookiecutter</a>  library, which is dedicated to that task, and that wouldn’t be a bad idea.</p>
<p>However, using Cookiecutter would mean learning Cookiecutter. Imagine you didn’t have much time, and your environment was extremely minimal anyway—all you could really count on was Git and Python. In these cases,  <code>subprocess</code>  can quickly set up your project for you:</p>
<p>Python</p>
<p>`# create_project.py</p>
<p>from argparse import ArgumentParser<br>
from pathlib import Path<br>
import subprocess</p>
<p>def create_new_project(name):<br>
project_folder = Path.cwd().absolute() / name<br>
project_folder.mkdir()<br>
(project_folder / “<a href="http://README.md">README.md</a>”).touch()<br>
with open(project_folder / “.gitignore”, mode=“w”) as f:<br>
f.write("\n".join([“venv”, “<strong>pycache</strong>”]))<br>
commands = [<br>
[<br>
“python”,<br>
“-m”,<br>
“venv”,<br>
f"{project_folder}/venv",<br>
],<br>
[“git”, “-C”, project_folder, “init”],<br>
[“git”, “-C”, project_folder, “add”, “.”],<br>
[“git”, “-C”, project_folder, “commit”, “-m”, “Initial commit”],<br>
]<br>
for command in commands:<br>
try:<br>
subprocess.run(command, check=True, timeout=60)<br>
except FileNotFoundError as exc:<br>
print(<br>
f"Command {command} failed because the process "<br>
f"could not be found.\n{exc}"<br>
)<br>
except subprocess.CalledProcessError as exc:<br>
print(<br>
f"Command {command} failed because the process "<br>
f"did not return a successful return code.\n{exc}"<br>
)<br>
except subprocess.TimeoutExpired as exc:<br>
print(f"Command {command} timed out.\n  {exc}")</p>
<p>if <strong>name</strong> == “<strong>main</strong>”:<br>
parser = ArgumentParser()<br>
parser.add_argument(“project_name”, type=str)<br>
args = parser.parse_args()<br>
create_new_project(args.project_name)`</p>
<p>This is a command-line tool that you can call to start a project. It’ll take care of creating a  <code>README.md</code>  file and a  <code>.gitignore</code>  file, and then it’ll run a few commands to create a virtual environment, initialize a git repository, and perform your first commit. It’s even cross-platform, opting to use  <code>pathlib</code>  to create the files and folders, which abstracts away the operating system differences.</p>
<p>Could this be done with Cookiecutter? Could you use  <a href="https://github.com/gitpython-developers/GitPython">GitPython</a>  for the  <code>git</code>  part? Could you use the  <code>venv</code>  module to create the virtual environment? Yes to all. But if you just need something quick and dirty, using commands you already know, then just using  <code>subprocess</code>  can be a great option.</p>
<h3 id="changing-extended-attributes">Changing Extended Attributes<a href="https://realpython.com/python-subprocess/#changing-extended-attributes" title="Permanent link"></a></h3>
<p>If you use Dropbox, you may not know that there’s a way to ignore files when syncing. For example, you can keep virtual environments in your project folder and use Dropbox to sync the code, but keep the virtual environment local.</p>
<p>That said, it’s not as easy as adding a  <code>.dropboxignore</code>  file. Rather, it involves adding special attributes to files, which can be done from the command line. These attributes are different between UNIX-like systems and Windows:</p>
<ul>
<li><a href="https://realpython.com/python-subprocess/#windows-5">Windows</a></li>
<li><a href="https://realpython.com/python-subprocess/#linux-5">Linux</a></li>
<li><a href="https://realpython.com/python-subprocess/#macos-5">macOS</a></li>
</ul>
<p>Shell</p>
<p><code>$ attr -s com.dropbox.ignored -V 1 \ /home/yourname/Dropbox/YourFileName.pdf</code></p>
<p>There are some UNIX-based projects, like  <a href="https://github.com/sp1thas/dropboxignore">dropboxignore</a>, that use shell scripts to make it easier to ignore files and folders. The code is relatively complex, and it won’t work on Windows.</p>
<p>With the  <code>subprocess</code>  module, you can wrap the different shell commands quite easily to come up with your own utility:</p>
<p>Python</p>
<p>``# dropbox_ignore.py</p>
<p>import platform<br>
from pathlib import Path<br>
from subprocess import run, DEVNULL</p>
<p>def init_shell():<br>
print(“initializing shell”)<br>
system = platform.system()<br>
print(f"{system} detected")<br>
if system == “Linux”:<br>
return Bash_shell()<br>
elif system == “Windows”:<br>
return Pwsh_shell()<br>
elif system == “Darwin”:<br>
raise NotImplementedError</p>
<p>class Pwsh_shell():<br>
def <strong>init</strong>(self) -&gt; None:<br>
try:<br>
run([“pwsh”, “-V”], stdout=DEVNULL, stderr=DEVNULL)<br>
self.shell = “pwsh”<br>
except FileNotFoundError as exc:<br>
print(“Powershell Core not installed, falling back to PowerShell”)<br>
self.shell = “powershell”</p>
<pre><code>@staticmethod
def _make_string_path_list(paths: list[Path]) -&gt; str:
    return "', '".join(str(path).replace("'", "`'") for path in paths)

def ignore_folders(self, paths: list[Path]) -&gt; None:
    path_list = self._make_string_path_list(paths)
    command = (
        f"Set-Content -Path '{path_list}' "
        f"-Stream com.dropbox.ignored -Value 1"
    )
    run([self.shell, "-NoProfile", "-Command", command], check=True)
    print("Done!")
</code></pre>
<p>class Bash_shell():<br>
@staticmethod<br>
def _make_string_path_list(paths: list[Path]) -&gt; str:<br>
return “’ '”.join(str(path).replace("’", “\’”) for path in paths)</p>
<pre><code>def ignore_folders(self, paths: list[Path]) -&gt; None:
    path_list = self._make_string_path_list(paths)
    command = (
        f"for f in '{path_list}'\n do\n "
        f"attr -s com.dropbox.ignored -V 1 $f\ndone"
    )
    run(["bash", "-c", command], check=True)
    print("Done!")`` 
</code></pre>
<p>This is a simplified snippet from the author’s  <a href="https://github.com/iansedano/dot_dropbox_ignore">dotDropboxIgnore</a>  repository. The  <code>init_shell()</code>  function detects the operating system with the  <a href="https://docs.python.org/3/library/platform.html"><code>platform</code></a>  module and returns an object that’s an abstraction around the system-specific shell. The code hasn’t implemented the behavior on macOS, so it raises a  <code>NotImplementedError</code>  if it detects it’s running on macOS.</p>
<p>The shell object allows you to call an  <code>.ignore_folders()</code>  method with a list of  <a href="https://realpython.com/python-pathlib/"><code>pathlib</code></a>  <a href="https://docs.python.org/3/library/pathlib.html#pathlib.Path"><code>Path</code></a>  objects to set Dropbox to ignore those files.</p>
<p>On the  <code>Pwsh_shell</code>  class, the constructor tests to see if PowerShell Core is available, and if not, will fall back to the older Windows PowerShell, which is installed by default on Windows 10.</p>
<p>In the next section, you’ll review some of the other modules that might be interesting to keep in mind when deciding whether to use  <code>subprocess</code>.</p>
<h2 id="python-modules-associated-with--subprocess">Python Modules Associated With  <code>subprocess</code><a href="https://realpython.com/python-subprocess/#python-modules-associated-with-subprocess" title="Permanent link"></a></h2>
<p>When deciding whether a certain task is a good fit for  <code>subprocess</code>, there are some associated modules that you may want to be aware of.</p>
<p>Before  <code>subprocess</code>  existed, you could use  <code>os.system()</code>  to run commands. However, as with many things that  <code>os</code>  was used for before, standard library modules have come to replace  <code>os</code>, so it’s mostly used internally. There are hardly any use cases for using  <code>os</code>  yourself.</p>
<p>There’s an  <a href="https://docs.python.org/3/library/subprocess.html#replacing-older-functions-with-the-subprocess-module">official documentation page</a>  where you can examine some of the old ways to accomplish tasks with  <code>os</code>  and learn how you might do the same with  <code>subprocess</code>.</p>
<p>It might be tempting to think that  <code>subprocess</code>  can be used for  <a href="https://realpython.com/python-concurrency/">concurrency</a>, and in simple cases, it can be. But, in line with the sloppy Python philosophy, it’s probably only going to be to hack something together quickly. If you want something more robust, then you’ll probably want to start looking at the  <code>multiprocessing</code>  module.</p>
<p>Depending on the task that you’re attempting, you may be able to accomplish it with the  <a href="https://realpython.com/async-io-python/"><code>asyncio</code></a>  or  <a href="https://realpython.com/intro-to-python-threading/"><code>threading</code></a>  modules. If everything is written in Python, then these modules are likely your best bet.</p>
<p>The  <code>asyncio</code>  module has a  <a href="https://docs.python.org/3/library/asyncio-subprocess.html">high-level API</a>  to create and manage subprocesses too, so if you want more control over non-Python parallel processes, that might be one to check out.</p>
<p>Now it’s time to get deep into  <code>subprocess</code>  and explore the underlying  <code>Popen</code>  class and its constructor.</p>
<h2 id="the--popen--class">The  <code>Popen</code>  Class<a href="https://realpython.com/python-subprocess/#the-popen-class" title="Permanent link"></a></h2>
<p>As mentioned, the underlying class for the whole  <code>subprocess</code>  module is the  <code>Popen</code>  class and the  <code>Popen()</code>  constructor. Each function in  <code>subprocess</code>  calls the  <code>Popen()</code>  constructor under the hood. Using the  <code>Popen()</code>  constructor gives you lots of control over the newly started subprocesses.</p>
<p>As a quick summary,  <code>run()</code>  is basically the  <code>Popen()</code>  class constructor, some setup, and then a call to the  <a href="https://docs.python.org/3/library/subprocess.html#subprocess.Popen.communicate"><code>.communicate()</code></a>  method on the newly initialized  <code>Popen</code>  object. The  <code>.communicate()</code>  method is a blocking method that returns the  <code>stdout</code>  and  <code>stderr</code>  data once the process has ended.</p>
<p>The name of  <code>Popen</code>  comes from a similar  <a href="https://man7.org/linux/man-pages/man3/popen.3.html">UNIX command</a>  that stands for  <em>pipe open</em>. The command creates a pipe and then starts a new process that invokes the shell. The  <code>subprocess</code>  module, though, doesn’t automatically invoke the shell.</p>
<p>The  <code>run()</code>  function is a  <strong>blocking function</strong>, which means that interacting dynamically with a process isn’t possible with it. However, the  <code>Popen()</code>  constructor starts a new process and continues, leaving the process running in  <em>parallel</em>.</p>
<p>The developer of the reaction game that you were hacking earlier has released a new version of their game, one in which you can’t cheat by loading  <code>stdin</code>  with newlines:</p>
<p>Python</p>
<p>`# reaction_game_v2.py</p>
<p>from random import choice, random<br>
from string import ascii_lowercase<br>
from time import perf_counter, sleep</p>
<p>print(<br>
“A letter will appear on screen after a random amount of time,\n”<br>
“when it appears, type the letter as fast as possible "<br>
“and then press enter\n”<br>
)<br>
print(“Press enter when you are ready”)<br>
input()<br>
print(“Ok, get ready!”)<br>
sleep(random() * 5 + 2)<br>
target_letter = choice(ascii_lowercase)<br>
print(f”=<mark><mark>\n= {target_letter} =\n</mark></mark>=\n")</p>
<p>start = perf_counter()<br>
while True:<br>
if input() == target_letter:<br>
break<br>
else:<br>
print(“Nope! Try again.”)<br>
end = perf_counter()</p>
<p>print(f"You reacted in {(end  -  start)  *  1000:.0f} milliseconds!\nGoodbye!")`</p>
<p>Now the program will display a random character, and you need to press that exact character to have the game register your reaction time:</p>
<p>What’s to be done? First, you’ll need to come to grips with using  <code>Popen()</code>  with basic commands, and then you’ll find another way to exploit the reaction game.</p>
<h3 id="using--popen">Using  <code>Popen()</code><a href="https://realpython.com/python-subprocess/#using-popen" title="Permanent link"></a></h3>
<p>Using the  <code>Popen()</code>  constructor is very similar in appearance to using  <code>run()</code>. If there’s an argument that you can pass to  <code>run()</code>, then you’ll generally be able to pass it to  <code>Popen()</code>. The fundamental difference is that it’s not a  <a href="https://en.wikipedia.org/wiki/Blocking_(computing)">blocking</a>  call—rather than waiting until the process is finished, it’ll run the process in parallel. So you need to take this non-blocking nature into account if you want to read the new process’s output:</p>
<p>Python</p>
<p>`# popen_timer.py</p>
<p>import subprocess<br>
from time import sleep</p>
<p>with subprocess.Popen(<br>
[“python”, “<a href="http://timer.py">timer.py</a>”, “5”], stdout=subprocess.PIPE<br>
) as process:</p>
<pre><code>def poll_and_read():
    print(f"Output from poll: {process.poll()}")
    print(f"Output from stdout: {process.stdout.read1().decode('utf-8')}")

poll_and_read()
sleep(3)
poll_and_read()
sleep(3)
poll_and_read()` 
</code></pre>
<p>This program calls the timer process in a  <a href="https://realpython.com/python-with-statement/">context manager</a>  and assigns  <code>stdout</code>  to a pipe. Then it runs the  <a href="https://docs.python.org/3/library/subprocess.html#subprocess.Popen.poll"><code>.poll()</code></a>  method on the  <code>Popen</code>  object and reads its  <code>stdout</code>.</p>
<p>The  <code>.poll()</code>  method is a basic method to check if a process is still running. If it is, then  <code>.poll()</code>  returns  <code>None</code>. Otherwise, it’ll return the process’s exit code.</p>
<p>Then the program uses  <a href="https://docs.python.org/3/library/io.html#io.BufferedIOBase.read1"><code>.read1()</code></a>  to try and read as many bytes as are available at  <code>.stdout</code>.</p>
<p><strong>Note:</strong>  If you put the  <code>Popen</code>  object into  <em>text mode</em>  and then called  <code>.read()</code>  on  <code>.stdout</code>, the call to  <code>.read()</code>  would be  <em>blocking</em>  until it reached a newline. In this case, a newline would coincide with the end of the timer program. This behavior isn’t desired in this situation.</p>
<p>To read as many bytes as are available at that time, disregarding newlines, you need to read with  <code>.read1()</code>. It’s important to note that  <code>.read1()</code>  is only available on byte streams, so you need to make sure to deal with encodings manually and not use  <em>text mode</em>.</p>
<p>The output of this program first prints  <code>None</code>  because the process hasn’t yet finished. The program then prints what is available in  <code>stdout</code>  so far, which is the starting message and the first character of the animation.</p>
<p>After three seconds, the timer hasn’t finished, so you get  <code>None</code>  again, along with two more characters of the animation. After another three seconds, the process has ended, so  <code>.poll()</code>  produces  <code>0</code>, and you get the final characters of the animation and  <code>Done!</code>:</p>
<p>Text</p>
<p><code>Output from poll: None Output from stdout: Starting timer of 5 seconds . Output from poll: None Output from stdout: .. Output from poll: 0 Output from stdout: ..Done!</code></p>
<p>In this example, you’ve seen how the  <code>Popen()</code>  constructor works very differently from  <code>run()</code>. In most cases, you don’t need this kind of fine-grained control. That said, in the next sections, you’ll see how you can pipe one process into another, and how you can hack the new reaction game.</p>
<h3 id="connecting-two-processes-together-with-pipes">Connecting Two Processes Together With Pipes<a href="https://realpython.com/python-subprocess/#connecting-two-processes-together-with-pipes" title="Permanent link"></a></h3>
<p>As mentioned in a  <a href="https://realpython.com/python-subprocess/#pipe-simulation-with-run">previous section</a>, if you need to connect processes together with pipes, you need to use the  <code>Popen()</code>  constructor. This is mainly because  <code>run()</code>  is a blocking call, so by the time the next process starts, the first one has ended, meaning that you can’t directly link up to its  <code>stdout</code>.</p>
<p>This procedure will only be demonstrated for UNIX systems, because piping in Windows is far less common, as mentioned in the  <a href="https://realpython.com/python-subprocess/#pipe-simulation-with-run">simulating a pipe</a>  section:</p>
<p>Python</p>
<p>`# popen_pipe.py</p>
<p>import subprocess</p>
<p>ls_process = subprocess.Popen([“ls”, “/usr/bin”], stdout=subprocess.PIPE)<br>
grep_process = subprocess.Popen(<br>
[“grep”, “python”], stdin=ls_process.stdout, stdout=subprocess.PIPE<br>
)</p>
<p>for line in grep_process.stdout:<br>
print(line.decode(“utf-8”).strip())`</p>
<p>In this example, the two processes are started in parallel. They are joined with a common pipe, and the  <code>for</code>  loop takes care of reading the pipe at  <code>stdout</code>  to output the lines.</p>
<p>A key point to note is that in contrast to  <code>run()</code>, which returns a  <code>CompletedProcess</code>  object, the  <code>Popen()</code>  constructor returns a  <code>Popen</code>  object. The standard stream attributes of a  <code>CompletedProcess</code>  point to  <em>bytes objects or strings</em>, but the same attributes of a  <code>Popen</code>  object point to the  <em>actual streams</em>. This allows you to communicate with processes as they’re running.</p>
<p>Whether you really need to pipe processes into one another, though, is another matter. Ask yourself if there’s much to be lost by mediating the process with Python and using  <code>run()</code>  exclusively. There are some situations in which you really need  <code>Popen</code>, though, such as hacking the new version of the reaction time game.</p>
<h3 id="interacting-dynamically-with-a-process">Interacting Dynamically With a Process<a href="https://realpython.com/python-subprocess/#interacting-dynamically-with-a-process" title="Permanent link"></a></h3>
<p>Now that you know you can use  <code>Popen()</code>  to interact with a process dynamically as it runs, it’s time to turn that knowledge toward exploiting the reaction time game again:</p>
<p>Python</p>
<p>`# reaction_game_v2_hack.py</p>
<p>import subprocess</p>
<p>def get_char(process):<br>
character = process.stdout.read1(1)<br>
print(<br>
character.decode(“utf-8”),<br>
end="",<br>
flush=True,  # Unbuffered print<br>
)<br>
return character.decode(“utf-8”)</p>
<p>def search_for_output(strings, process):<br>
buffer = “”<br>
while not any(string in buffer for string in strings):<br>
buffer = buffer + get_char(process)</p>
<p>with subprocess.Popen(<br>
[<br>
“python”,<br>
“-u”,  # Unbuffered stdout and stderr<br>
“reaction_game_v2.py”,<br>
],<br>
stdin=subprocess.PIPE,<br>
stdout=subprocess.PIPE,<br>
) as process:<br>
process.stdin.write(b"\n")<br>
process.stdin.flush()<br>
search_for_output(["<mark>\n= ", "</mark>\r\n= “], process)<br>
target_char = get_char(process)<br>
stdout, stderr = process.communicate(<br>
input=f”{target_char}\n".encode(“utf-8”), timeout=10<br>
)<br>
print(stdout.decode(“utf-8”))`</p>
<p>With this script, you’re taking complete control of the buffering of a process, which is why you pass in arguments such as  <code>-u</code>  to the Python process and  <a href="https://realpython.com/python-flush-print-output/"><code>flush=True</code>  to  <code>print()</code></a>. These arguments are to ensure that no extra buffering is taking place.</p>
<p>The script works by using a function that’ll search for one of a list of strings by grabbing one character at a time from the process’s  <code>stdout</code>. As each character comes through, the script will search for the string.</p>
<p><strong>Note:</strong>  To make this work on both Windows and UNIX-based systems, two strings are searched for: either  <code>"==\n= "</code>  or  <code>"==\r\n= "</code>. The Windows-style  <a href="https://en.wikipedia.org/wiki/Carriage_return">carriage return</a>  along with the typical newline is required on Windows systems.</p>
<p>After the script has found one of the target strings, which in this case is the sequence of characters before the target letter, it’ll then grab the next character and write that letter to the process’s  <code>stdin</code>  followed by a newline:</p>
<p>At one millisecond, it’s not quite as good as the original hack, but it’s still very much superhuman. Well done!</p>
<p>With all this fun aside, interacting with processes using  <code>Popen</code>  can be very tricky and is prone to errors. First, see if you can use  <code>run()</code>  exclusively before resorting to the  <code>Popen()</code>  constructor.</p>
<p>If you really need to interact with processes at this level, the  <a href="https://realpython.com/async-io-python/"><code>asyncio</code></a>  module has a  <a href="https://docs.python.org/3/library/asyncio-subprocess.html">high-level API</a>  to create and manage subprocesses.</p>
<p>The  <code>asyncio</code>  subprocess functionality is intended for more complex uses of  <code>subprocess</code>  where you may need to orchestrate various processes. This might be the case if you’re performing complex processing of many image, video, or audio files, for example. If you’re using  <code>subprocess</code>  at this level, then you’re probably building a library.</p>
<h2 id="conclusion">Conclusion<a href="https://realpython.com/python-subprocess/#conclusion" title="Permanent link"></a></h2>
<p>You’ve completed your journey into the Python  <code>subprocess</code>  module. You should now be able to decide whether  <code>subprocess</code>  is a good fit for your problem. You should also be able to decide whether you need to invoke the shell. Aside from that, you should be able to run subprocesses and interact with their inputs and outputs.</p>
<p>You should also be able to start exploring the possibilities of process manipulation with the  <code>Popen()</code>  constructor.</p>
<p>Along the way, you’ve:</p>
<ul>
<li>Learned about  <strong>processes in general</strong></li>
<li>Gone from basic to advanced  <strong>usage of  <code>subprocess</code></strong></li>
<li>Understood how to  <strong>raise and handle errors</strong>  when using  <code>run()</code></li>
<li>Gotten familiar with  <strong>shells</strong>  and their intricacies on both  <strong>Windows and UNIX-like systems</strong></li>
<li>Explored the  <strong>use cases for  <code>subprocess</code></strong>  through  <strong>practical examples</strong></li>
<li>Understood the standard  <strong>I/O streams</strong>  and how to  <strong>interact with them</strong></li>
<li>Come to grips with  <strong>pipes</strong>, both in the shell and with  <code>subprocess</code></li>
<li>Looked at the  <strong><code>Popen()</code>  constructor</strong>  and used it for some advanced process communication</li>
</ul>
<p>You’re now ready to bring a variety of executables into your Pythonic sphere of influence!</p>
<h4 id="section"></h4>
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
 <span class="token comment">### 2. **Key-Value Pairs:**</span>

<span class="token punctuation">-</span> YAML uses a simple key<span class="token punctuation">-</span>value format. Keys and values are separated by a colon<span class="token punctuation">,</span> and the key<span class="token punctuation">-</span>value pair is represented on a new line.

```yaml
<span class="token key atrule">codename</span><span class="token punctuation">:</span> John Doe
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
<h1 id="section-1">…</h1>
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
<h1 id="from-django-to-hugo---mauro-project---djungo">FROM DJANGO TO HUGO - Mauro Project - DJUNGO</h1>
<h1 id="integrazione-esterna---creare-un-post-da-django-a-hugo">Integrazione Esterna - Creare un POST da Django a Hugo</h1>
<p>Abbiamo realizzato un’integrazione tra Django e Hugo che permette di creare, cancellare e aggiornare i post sul sito statico gestito da Hugo direttamente dall’admin panel di Django. Ecco una sintesi di ciò che abbiamo fatto:</p>
<h2 id="creazione-di-post"><strong>Creazione di Post</strong>:</h2>
<pre><code>-   In Django, abbiamo configurato un'azione che consente agli utenti di creare nuovi post per il sito Hugo tramite l'admin panel.
-   Quando si crea un nuovo post in Django, vengono raccolte tutte le informazioni necessarie, come titolo, data, tag, categorie, e link dell'immagine.
-   Questi dati vengono passati a uno script Bash (`**manage_posts.sh**`), che genera un file Markdown nella directory dei contenuti di Hugo con i dettagli del post.
-   Il file creato contiene tutte le informazioni nel formato TOML, necessario affinché Hugo possa renderizzare correttamente il post.
</code></pre>
<h2 id="cancellazione-di-post"><strong>Cancellazione di Post</strong>:</h2>
<pre><code>-   Sempre tramite l'admin panel di Django, è possibile selezionare e cancellare uno o più post.
-   Quando un post viene cancellato in Django, lo stesso script Bash viene richiamato per eliminare il file Markdown corrispondente dalla directory di Hugo.
-   Questo assicura che il post sia rimosso sia dal database di Django che dal sito Hugo.
</code></pre>
<h2 id="aggiornamento-di-post"><strong>Aggiornamento di Post</strong>:</h2>
<pre><code>-   Abbiamo introdotto una funzione che permette di aggiornare un post esistente. Se si tenta di creare un post con un nome che già esiste, si può scegliere di aggiornare il contenuto esistente.
-   Lo script Bash viene richiamato per sovrascrivere il file esistente con le nuove informazioni fornite dall'admin panel di Django.
</code></pre>
<h2 id="integrazione-dei-link-delle-immagini"><strong>Integrazione dei Link delle Immagini</strong>:</h2>
<pre><code>-   Abbiamo configurato il sistema per gestire correttamente i link delle immagini. Se fornito, il link dell'immagine viene utilizzato nel file Markdown del post; in caso contrario, viene utilizzata un'immagine di default.
</code></pre>
<p>In sintesi, abbiamo automatizzato la gestione dei contenuti di un sito Hugo direttamente tramite Django, facilitando la creazione, l’aggiornamento e la cancellazione dei post senza dover intervenire manualmente sui file del sito statico.</p>
<p>Ecco il codice definitivo per integrare la gestione dei post di Hugo tramite Django, inclusi la creazione, cancellazione e aggiornamento dei post:</p>
<h3 id="codice-di-admin.py">Codice di <code>admin.py</code></h3>
<pre><code>`import os
import subprocess
from django.contrib import admin
from .models import Post

@admin.register(Post)
class PostAdmin(admin.ModelAdmin):
    list_display = ('title', 'file_name', 'image_name', 'image_link')

    def run_manage_posts_script(self, request, action, **kwargs):
        try:
            script_path = os.path.abspath(
                os.path.join(os.path.dirname(__file__), '..', 'sgb_start', 'manage_posts.sh')
            )
            env = os.environ.copy()
            env['PATH'] = '/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:' + env.get('PATH', '')

            # Esegui il comando di creazione o cancellazione
            result = subprocess.run(
                [script_path, action, *kwargs.values()],
                capture_output=True, text=True, check=True, env=env
            )

            if result.returncode == 0:
                self.message_user(request, "Manage posts script executed successfully")
            else:
                self.message_user(request, f"Manage posts script execution failed: {result.stderr}", level='ERROR')
        except subprocess.CalledProcessError as e:
            self.message_user(request, f"Manage posts script execution failed: {e.stderr}", level='ERROR')
        except Exception as e:
            self.message_user(request, f"Unexpected error: {e}", level='ERROR')

    def add_post_action(self, request, queryset):
        for post in queryset:
            post_name = post.title.replace(' ', '_').lower()
            title = post.title
            date = post.date.strftime('%Y-%m-%dT%H:%M:%S%z')
            tags = post.tags
            categories = post.categories
            image = post.image_link
            image_alt = post.image_alt
            image_caption = post.image_caption

            self.run_manage_posts_script(
                request, 'add',
                post_name=post_name,
                title=title,
                date=date,
                tags=tags,
                categories=categories,
                image=image,
                image_alt=image_alt,
                image_caption=image_caption
            )

    add_post_action.short_description = "Add a new post"
    actions = ['add_post_action', 'delete_selected_posts', 'update_selected_posts']

    def delete_selected_posts(self, request, queryset):
        for post in queryset:
            self.run_manage_posts_script(
                request, 'delete', 
                post_name=post.file_name.replace('.md', '')
            )
            post.delete()
        self.message_user(request, "Selected posts have been deleted.")

    delete_selected_posts.short_description = "Delete selected posts"

    def get_actions(self, request):
        actions = super().get_actions(request)
        if 'delete_selected' in actions:
            del actions['delete_selected']
        return actions` 
</code></pre>
<h3 id="codice-di-manage_posts.sh">Codice di <code>manage_posts.sh</code></h3>
<pre><code>`#!/bin/bash

# Log file per il debug
LOG_FILE="/home/mauro/Scrivania/dJANGO_apI/progetto_api/sgb_start/manage_posts.log"
echo "Script called with action: $1" &gt;&gt; "$LOG_FILE"

# Directory contenente i post
POSTS_DIR="/home/mauro/Scrivania/dJANGO_apI/progetto_api/sgb_start/content/posts"
echo "Posts directory: $POSTS_DIR" &gt;&gt; "$LOG_FILE"

# Controlla se la directory dei post esiste
if [ ! -d "$POSTS_DIR" ]; then
  echo "Directory $POSTS_DIR does not exist." &gt;&gt; "$LOG_FILE"
  exit 1
fi

# Funzione per creare o aggiornare un post
create_post() {
  POST_NAME="$1.md"
  POST_TITLE="$2"
  POST_DATE="$3"
  POST_TAGS="$4"
  POST_CATEGORIES="$5"
  POST_IMAGE="$6"
  POST_IMAGE_ALT="$7"
  POST_IMAGE_CAPTION="$8"

  echo "Creating or updating post with name: $POST_NAME" &gt;&gt; "$LOG_FILE"
  echo "Image link: $POST_IMAGE" &gt;&gt; "$LOG_FILE"

  # Format tags and categories for TOML
  formatted_tags=$(echo "$POST_TAGS" | sed 's/ *, */", "/g' | sed 's/^/["/' | sed 's/$/"]/')
  formatted_categories=$(echo "$POST_CATEGORIES" | sed 's/ *, */", "/g' | sed 's/^/["/' | sed 's/$/"]/')

  # Crea o aggiorna il file del post
  POST_FILE="$POSTS_DIR/$POST_NAME"
  cat &lt;&lt;EOF &gt; "$POST_FILE"
+++
title = "$POST_TITLE"
date = "$POST_DATE"
draft = true
ShowToc = true
tags = $formatted_tags
categories = $formatted_categories
[cover]
    image = "$POST_IMAGE"
    alt = "$POST_IMAGE_ALT"
    caption = "$POST_IMAGE_CAPTION"
+++
EOF

  echo "Post '$POST_NAME' has been created or updated at $POST_FILE." &gt;&gt; "$LOG_FILE"
}

# Funzione per cancellare un post
delete_post() {
  POST_NAME="$1.md"
  echo "Deleting post with name: $POST_NAME" &gt;&gt; "$LOG_FILE"
  if [ -f "$POSTS_DIR/$POST_NAME" ]; then
    rm "$POSTS_DIR/$POST_NAME"
    echo "Post '$POST_NAME' has been deleted." &gt;&gt; "$LOG_FILE"
  else
    echo "Post '$POST_NAME' does not exist." &gt;&gt; "$LOG_FILE"
  fi
}

# Logica principale dello script
ACTION="$1"
shift

case "$ACTION" in
  add|update)
    create_post "$@"
    ;;
  delete)
    delete_post "$1"
    ;;
  *)
    echo "Invalid action. Use 'add', 'update', or 'delete'." &gt;&gt; "$LOG_FILE"
    exit 1
    ;;
esac` 
</code></pre>
<h3 id="files-django-di-supporto">Files Django di supporto</h3>
<p><a href="http://apps.py">apps.py</a></p>
<pre><code>from  django.apps  import  AppConfig

  
  

class  BlogConfig(AppConfig):

default_auto_field  =  "django.db.models.BigAutoField"

name  =  "blog"
</code></pre>
<p><a href="http://models.py">models.py</a>:</p>
<pre><code>from  django.db  import  models

from  django.utils  import  timezone

  

class  Post(models.Model):

title  =  models.CharField(max_length=255)

file_name  =  models.CharField(max_length=255, unique=True)

date  =  models.DateTimeField(default=timezone.now)

tags  =  models.CharField(max_length=255, default="adventure,foodie,travel,fitness,nature,fun,inspiration")

categories  =  models.CharField(max_length=255, default="adventure,food,health,art,entertainment,science,lifestyle")

image_name  =  models.CharField(max_length=255)

image_alt  =  models.CharField(max_length=255, default="Default Alt Text")

image_caption  =  models.CharField(max_length=255, default="Default Caption")

image_link  =  models.URLField()

draft  =  models.BooleanField(default=True)

  

def  __str__(self):

return  self.title
</code></pre>
<p>Con questo codice, siamo riusciti a collegare Django e Hugo, permettendo di gestire i post del sito Hugo direttamente dall’admin panel di Django, con la possibilità di creare, aggiornare e cancellare post in modo semplice ed efficiente.</p>
<h1 id="integrazione-interna---aggiornare-un-database-da-django-a-hugo">Integrazione Interna - Aggiornare un database da Django a Hugo</h1>
<h2 id="step-by-step-guide-to-integrate-django-api-with-hugo">Step-by-Step Guide to Integrate Django API with Hugo</h2>
<p>We want to create an API in Django that can be consumed by a Hugo site, allowing data to be transferred (added, deleted, updated) from Django to Hugo. Here’s how you can achieve this:</p>
<h3 id="set-up-django-api">1. <strong>Set Up Django API</strong></h3>
<h4 id="models-the-nation-model-is-already-defined-in-your-models.py-file"><strong>Models:</strong> The <code>Nation</code> model is already defined in your <code>models.py</code> file:</h4>
<pre><code>`from django.db import models

class Nation(models.Model):
    name = models.CharField(max_length=255, unique=True)
    capital = models.CharField(max_length=255)

    def __str__(self):
        return self.name` 
</code></pre>
<h4 id="serializers-the-nationserializer-in-serializers.py-will-serialize-the-nation-model-data-to-json"><strong>Serializers:</strong> The <code>NationSerializer</code> in <code>serializers.py</code> will serialize the <code>Nation</code> model data to JSON:</h4>
<pre><code>`from rest_framework import serializers
from .models import Nation

class NationSerializer(serializers.ModelSerializer):
    class Meta:
        model = Nation
        fields = '__all__'` 
</code></pre>
<h4 id="views-in-views.py-create-an-api-view-using-django-rest-framework"><strong>Views:</strong> In <code>views.py</code>, create an API view using Django REST Framework:</h4>
<pre><code>`from rest_framework.response import Response
from rest_framework import status
from rest_framework.views import APIView
from .models import Nation
from .serializers import NationSerializer

class NationAPIView(APIView):
    def get(self, request):
        nations = Nation.objects.all()
        serializer = NationSerializer(nations, many=True)
        return Response(serializer.data, status=status.HTTP_200_OK)

    def post(self, request):
        serializer = NationSerializer(data=request.data)
        if serializer.is_valid():
            serializer.save()
            return Response(serializer.data, status=status.HTTP_201_CREATED)
        return Response(serializer.errors, status=status.HTTP_400_BAD_REQUEST)

    def delete(self, request, pk):
        try:
            nation = Nation.objects.get(pk=pk)
            nation.delete()
            return Response(status=status.HTTP_204_NO_CONTENT)
        except Nation.DoesNotExist:
            return Response(status=status.HTTP_404_NOT_FOUND)` 
</code></pre>
<h4 id="urls-map-the-view-to-a-url-in-urls.py"><strong>URLs:</strong> Map the view to a URL in <code>urls.py</code>:</h4>
<pre><code>`from django.urls import path
from .views import NationAPIView

urlpatterns = [
    path('nations/', NationAPIView.as_view(), name='nation-api'),
]` 
</code></pre>
<h3 id="hugo-integration">2. <strong>Hugo Integration</strong></h3>
<p>In your Hugo project, you can fetch data from the Django API and display it on the site.</p>
<h4 id="template-code-in-layoutsdjango_retrievesingle.html-you-already-have-the-code-to-fetch-the-data"><strong>Template Code:</strong> In <code>layouts/django_retrieve/single.html</code>, you already have the code to fetch the data:</h4>
<pre><code>``&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8"&gt;
  &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
  &lt;title&gt;Nations and Capitals&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
  &lt;h1&gt;Nations and Capitals&lt;/h1&gt;
  &lt;ul id="nationList"&gt;&lt;/ul&gt;

  &lt;script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"&gt;&lt;/script&gt;
  &lt;script&gt; document.addEventListener('DOMContentLoaded', fetchData);

    async function fetchData() {
      try {
        const response = await axios.get('http://127.0.0.1:8000/django_api_for_wagtail/nations/?format=json');
        const nations = response.data;
        displayNations(nations);
      } catch (error) {
        console.error('Error fetching data:', error);
      }
    }

    function displayNations(nations) {
      const nationList = document.getElementById('nationList');
      nationList.innerHTML = '';

      nations.forEach(nation =&gt; {
        const li = document.createElement('li');
        li.innerHTML = `&lt;span&gt;Nazione: ${nation.name}&lt;/span&gt; &lt;span&gt;Capital: ${nation.capital}&lt;/span&gt;`;
        nationList.appendChild(li);
      });
    }

    setInterval(fetchData, 5000); // Optional: Refresh data every 5 seconds &lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;`` 
</code></pre>
<p>This JavaScript code fetches the list of nations from the Django API and displays them on your Hugo site.</p>
<h3 id="updating-the-django-admin-to-push-data-to-hugo">3. <strong>Updating the Django Admin to Push Data to Hugo</strong></h3>
<p>In <code>admin.py</code>, you can add functionality to push data directly to Hugo using Django admin actions. We’ve already covered how to handle adding, deleting, and updating posts in Hugo using the Django admin interface.</p>
<h3 id="testing-the-integration">4. <strong>Testing the Integration</strong></h3>
<ul>
<li><strong>Start Django Server:</strong> Make sure your Django server is running (<code>python manage.py runserver</code>).</li>
<li><strong>Start Hugo Server:</strong> Start the Hugo server (<code>hugo server</code>).</li>
<li><strong>Test the API:</strong> Use tools like <code>curl</code>, Postman, or your browser to interact with the Django API.</li>
<li><strong>Check Hugo:</strong> Open your Hugo site and check if the data from Django is reflected correctly.</li>
</ul>
<p>With these steps, you’ve set up a fully functional API in Django that interacts with a Hugo site, allowing you to manage content across both platforms seamlessly.</p>
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
<h3 id="step-17-bis-problems-with-git-push">Step 17 bis: problems with git push</h3>
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
<h3 id="step-18-verify-github-repository">Step 18: Verify GitHub Repository</h3>
<p>Go to your GitHub repository in the web browser and verify that your code has been pushed successfully.</p>
<p>That’s it! Now you have a Django project with a superuser account, and your code is version-controlled using Git and hosted on GitHub.</p>
<h3 id="step-19-create-models-views-and-templates-optional">Step 19: Create Models, Views, and Templates (Optional)</h3>
<p>You can now start building your Django app by creating models, views, and templates. Define your models in the <code>models.py</code> file, create views in the <code>views.py</code> file, and add templates in the <code>templates</code> directory.</p>
<h3 id="step-20-create-api-app-optional">Step 20: Create API App (Optional)</h3>
<p>If you want to create a separate app for your API, follow the instructions provided in the previous response to create an <code>api</code> app and set up serializers, views, and URLs.</p>
<p>That’s it! You now have a basic Django project and app set up. Customize it based on your specific requirements and integrate it with your Wagtail project as needed.</p>
<h2 id="working-with-django-app">Working with Django APP</h2>
<h3 id="add-new-database-in-the-app">Add new database in the app</h3>
<p>To create a new model in your Django <code>blog</code> app that holds information about files, images, text, and image links, you can modify your <code>models.py</code> file as follows:</p>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> django<span class="token punctuation">.</span>db <span class="token keyword">import</span> models

<span class="token keyword">class</span> <span class="token class-name">Post</span><span class="token punctuation">(</span>models<span class="token punctuation">.</span>Model<span class="token punctuation">)</span><span class="token punctuation">:</span>
    title <span class="token operator">=</span> models<span class="token punctuation">.</span>CharField<span class="token punctuation">(</span>max_length<span class="token operator">=</span><span class="token number">255</span><span class="token punctuation">)</span>
    text <span class="token operator">=</span> models<span class="token punctuation">.</span>TextField<span class="token punctuation">(</span><span class="token punctuation">)</span>
    file_name <span class="token operator">=</span> models<span class="token punctuation">.</span>CharField<span class="token punctuation">(</span>max_length<span class="token operator">=</span><span class="token number">255</span><span class="token punctuation">,</span> unique<span class="token operator">=</span><span class="token boolean">True</span><span class="token punctuation">)</span>  <span class="token comment"># Name of the file</span>
    image_name <span class="token operator">=</span> models<span class="token punctuation">.</span>CharField<span class="token punctuation">(</span>max_length<span class="token operator">=</span><span class="token number">255</span><span class="token punctuation">)</span>  <span class="token comment"># Name of the image</span>
    image_link <span class="token operator">=</span> models<span class="token punctuation">.</span>URLField<span class="token punctuation">(</span><span class="token punctuation">)</span>  <span class="token comment"># Link to the image</span>

    <span class="token keyword">def</span> <span class="token function">__str__</span><span class="token punctuation">(</span>self<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">return</span> self<span class="token punctuation">.</span>title
</code></pre>
<p>In this model:</p>
<ul>
<li><code>title</code>: Represents the title of the post.</li>
<li><code>text</code>: Represents the content of the post (text).</li>
<li><code>file_name</code>: Represents the name of the file produced by your autogenerative Python code.</li>
<li><code>image_name</code>: Represents the name of the associated image.</li>
<li><code>image_link</code>: Represents the link to the image.</li>
</ul>
<p>You can adjust the field types and lengths according to your requirements.</p>
<pre><code>
Once the model is created and migrated, you can register it in the Django admin site to manage it:

```python
from django.contrib import admin
from .models import Post

@admin.register(Post)
class PostAdmin(admin.ModelAdmin):
    list_display = ('title', 'file_name', 'image_name', 'image_link')
</code></pre>
<p>After defining the model, don’t forget to run the following commands to create and apply the migrations:</p>
<pre class=" language-bash"><code class="prism  language-bash">python manage.py makemigrations
python manage.py migrate
</code></pre>
<p>With this setup, you’ll be able to add, edit, and delete posts with associated file names, image names, and image links through the Django admin interface. You can also access and manipulate this data programmatically through your Django views and templates as needed.</p>
<h3 id="step-21-create-a-command-to-populate-django-admin-from-content-files-directory-from-hugo">Step 21: Create a command to populate Django Admin from /content files directory from Hugo:</h3>
<pre><code>bash
#!/bin/bash
</code></pre>
<h1 id="directory-containing-markdown-files">Directory containing markdown files</h1>
<p>markdown_dir="/home/mauro/Scrivania/dJANGO_apI/progetto_api/sgb_start/content/posts/"</p>
<h1 id="output-file-to-store-processed-file-details">Output file to store processed file details</h1>
<p>output_file="/home/mauro/Scrivania/dJANGO_apI/progetto_api/blog/processed_files.txt"</p>
<h1 id="check-if-the-directory-exists">Check if the directory exists</h1>
<p>if [ !  -d  “$markdown_dir” ]; then</p>
<p>echo  “Error: Directory $markdown_dir does not exist.”</p>
<p>exit  1</p>
<p>fi</p>
<h1 id="create-or-clear-the-output-file">Create or clear the output file</h1>
<blockquote>
<p>“$output_file”</p>
</blockquote>
<h1 id="iterate-over-all-markdown-files-in-the-directory">Iterate over all markdown files in the directory</h1>
<p>for  markdown_file  in  “$markdown_dir”/*.md; do</p>
<p>if [ -f  “$markdown_file” ]; then</p>
<h1 id="read-contents-of-the-markdown-file-and-escape-problematic-characters">Read contents of the markdown file and escape problematic characters</h1>
<p>content=<span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo stretchy="false">(</mo><mi>c</mi><mi>a</mi><mi>t</mi><mi mathvariant="normal">"</mi></mrow><annotation encoding="application/x-tex">(cat  "</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal">c</span><span class="mord mathnormal">a</span><span class="mord mathnormal">t</span><span class="mord">"</span></span></span></span></span>markdown_file"  |  sed  ‘s/"/\"/g’  |  sed  “s/’/\’/g”  |  tr  ‘\n’  ’ ')</p>
<h1 id="extract-title-from-filename">Extract title from filename</h1>
<p>filename=<span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo stretchy="false">(</mo><mi>b</mi><mi>a</mi><mi>s</mi><mi>e</mi><mi>n</mi><mi>a</mi><mi>m</mi><mi>e</mi><mo>−</mo><mo>−</mo><mi mathvariant="normal">"</mi></mrow><annotation encoding="application/x-tex">(basename  --  "</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 1em; vertical-align: -0.25em;"></span><span class="mopen">(</span><span class="mord mathnormal">ba</span><span class="mord mathnormal">se</span><span class="mord mathnormal">nam</span><span class="mord mathnormal">e</span><span class="mspace" style="margin-right: 0.222222em;"></span><span class="mbin">−</span><span class="mspace" style="margin-right: 0.222222em;"></span></span><span class="base"><span class="strut" style="height: 0.77777em; vertical-align: -0.08333em;"></span><span class="mord">−</span><span class="mord">"</span></span></span></span></span>markdown_file")</p>
<p>title="${filename%.*}"</p>
<h1 id="construct-image_link-based-on-the-extracted-title">Construct image_link based on the extracted title</h1>
<p>image_link=“<a href="http://localhost:1313/posts/$%7Btitle%7D/">http://localhost:1313/posts/${title}/</a>”</p>
<h1 id="print-the-details-for-demonstration-purposes">Print the details (for demonstration purposes)</h1>
<p>echo  “Title: $title”</p>
<p>echo  “File Name: $filename”</p>
<p>echo  “Content: $content”</p>
<p>echo  “Image Link: $image_link”</p>
<p>echo  “-------------------------”</p>
<h1 id="save-the-data-to-the-django-database-using-the-django-shell">Save the data to the Django database using the Django shell</h1>
<p>echo  “from blog.models import Post; Post.objects.create(title=“<span class="katex--inline">KaTeX parse error: Can't use function '\"' in math mode at position 6: title\̲"̲, text=\"</span>content”, file_name=“<span class="katex--inline">KaTeX parse error: Can't use function '\"' in math mode at position 9: filename\̲"̲, image_name=''…</span>image_link”)”  |  python3  <a href="http://manage.py">manage.py</a>  shell</p>
<h1 id="log-the-details-to-the-output-file">Log the details to the output file</h1>
<p>echo  “Title: <span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>t</mi><mi>i</mi><mi>t</mi><mi>l</mi><mi>e</mi><mi mathvariant="normal">"</mi><mo>&gt;</mo><mo>&gt;</mo><mi mathvariant="normal">"</mi></mrow><annotation encoding="application/x-tex">title"  &gt;&gt;  "</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.73354em; vertical-align: -0.0391em;"></span><span class="mord mathnormal">t</span><span class="mord mathnormal">i</span><span class="mord mathnormal" style="margin-right: 0.01968em;">tl</span><span class="mord mathnormal">e</span><span class="mord">"</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">&gt;&gt;</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 0.69444em; vertical-align: 0em;"></span><span class="mord">"</span></span></span></span></span>output_file”</p>
<p>echo  “File Name: <span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>f</mi><mi>i</mi><mi>l</mi><mi>e</mi><mi>n</mi><mi>a</mi><mi>m</mi><mi>e</mi><mi mathvariant="normal">"</mi><mo>&gt;</mo><mo>&gt;</mo><mi mathvariant="normal">"</mi></mrow><annotation encoding="application/x-tex">filename"  &gt;&gt;  "</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.88888em; vertical-align: -0.19444em;"></span><span class="mord mathnormal" style="margin-right: 0.10764em;">f</span><span class="mord mathnormal">i</span><span class="mord mathnormal" style="margin-right: 0.01968em;">l</span><span class="mord mathnormal">e</span><span class="mord mathnormal">nam</span><span class="mord mathnormal">e</span><span class="mord">"</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">&gt;&gt;</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 0.69444em; vertical-align: 0em;"></span><span class="mord">"</span></span></span></span></span>output_file”</p>
<p>echo  “Content: <span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>c</mi><mi>o</mi><mi>n</mi><mi>t</mi><mi>e</mi><mi>n</mi><mi>t</mi><mi mathvariant="normal">"</mi><mo>&gt;</mo><mo>&gt;</mo><mi mathvariant="normal">"</mi></mrow><annotation encoding="application/x-tex">content"  &gt;&gt;  "</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.73354em; vertical-align: -0.0391em;"></span><span class="mord mathnormal">co</span><span class="mord mathnormal">n</span><span class="mord mathnormal">t</span><span class="mord mathnormal">e</span><span class="mord mathnormal">n</span><span class="mord mathnormal">t</span><span class="mord">"</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">&gt;&gt;</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 0.69444em; vertical-align: 0em;"></span><span class="mord">"</span></span></span></span></span>output_file”</p>
<p>echo  “Image Link: <span class="katex--inline"><span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mi>i</mi><mi>m</mi><mi>a</mi><mi>g</mi><msub><mi>e</mi><mi>l</mi></msub><mi>i</mi><mi>n</mi><mi>k</mi><mi mathvariant="normal">"</mi><mo>&gt;</mo><mo>&gt;</mo><mi mathvariant="normal">"</mi></mrow><annotation encoding="application/x-tex">image_link"  &gt;&gt;  "</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="base"><span class="strut" style="height: 0.88888em; vertical-align: -0.19444em;"></span><span class="mord mathnormal">ima</span><span class="mord mathnormal" style="margin-right: 0.03588em;">g</span><span class="mord"><span class="mord mathnormal">e</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 0.336108em;"><span class="" style="top: -2.55em; margin-left: 0em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathnormal mtight" style="margin-right: 0.01968em;">l</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.15em;"><span class=""></span></span></span></span></span></span><span class="mord mathnormal" style="margin-right: 0.03148em;">ink</span><span class="mord">"</span><span class="mspace" style="margin-right: 0.277778em;"></span><span class="mrel">&gt;&gt;</span><span class="mspace" style="margin-right: 0.277778em;"></span></span><span class="base"><span class="strut" style="height: 0.69444em; vertical-align: 0em;"></span><span class="mord">"</span></span></span></span></span>output_file”</p>
<p>echo  “-------------------------”  &gt;&gt;  “$output_file”</p>
<p>else</p>
<p>echo  “Error: $markdown_file is not a valid file.”</p>
<p>fi</p>
<p>done</p>
<p>echo  “Processing complete. Details stored in $output_file.”<br>
In <a href="http://admin.py">admin.py</a>:</p>
<pre><code>python
</code></pre>
<p>from  django.contrib  import  admin</p>
<p>from .models  import  CustomFeature</p>
<p>import  os</p>
<p>import  subprocess</p>
<p>from .models  import  Post</p>
<p>@admin.register(CustomFeature)</p>
<p>class  CustomFeatureAdmin(admin.ModelAdmin):</p>
<p>list_display  = (‘name’, ‘description’)</p>
<p>def  run_script(self, request, queryset):</p>
<p>try:</p>
<h1 id="this-line-retrieves-the-directory-path-of-the-current-python-script-admin.py-in-this-case-using-file">This line retrieves the directory path of the current Python script (<a href="http://admin.py">admin.py</a> in this case) using <strong>file</strong>,</h1>
<h1 id="which-is-a-special-attribute-in-python-that-represents-the-current-file-path.">which is a special attribute in Python that represents the current file path.</h1>
<p>current_dir  =  os.path.dirname(<strong>file</strong>)</p>
<p>script_path  =  os.path.abspath(os.path.join(current_dir, ‘add_page.sh’))</p>
<p>print(“Absolute path to script:”, script_path) # Print out the absolute path</p>
<p>subprocess.run([script_path], check=True)</p>
<p>self.message_user(request, “Script executed successfully”)</p>
<p>except  Exception  as  e:</p>
<p>self.message_user(request, f"Script execution failed: {e}", level=‘ERROR’)</p>
<p>run_script.short_description =  “Run add_page.sh”</p>
<p>actions  = [run_script]</p>
<p>from .models  import  Post</p>
<p>@admin.register(Post)</p>
<p>class  PostAdmin(admin.ModelAdmin):</p>
<p>list_display  = (‘title’, ‘file_name’, ‘image_name’, ‘image_link’)</p>
<p>def  populate_posts(self, request, queryset):</p>
<p>try:</p>
<p>current_dir  =  os.path.dirname(<strong>file</strong>)</p>
<p>script_path  =  os.path.abspath(os.path.join(current_dir, ‘populate_posts.sh’))</p>
<p>subprocess.run([script_path], check=True)</p>
<p>self.message_user(request, “Posts populated successfully”)</p>
<p>except  Exception  as  e:</p>
<p>self.message_user(request, f"Failed to populate posts: {e}", level=‘ERROR’)</p>
<p>populate_posts.short_description =  “Run populate_posts.sh”</p>
<p>actions  = [populate_posts]<br>
in <a href="http://models.py">models.py</a>:</p>
<pre><code>python
from  django.db  import  models
</code></pre>
<h1 id="create-your-models-here.-mauro">Create your models here. Mauro</h1>
<p>class  CustomFeature(models.Model):</p>
<p>name  =  models.CharField(max_length=255, unique=True)</p>
<p>description  =  models.TextField()</p>
<p>def  <strong>str</strong>(self):</p>
<p>return  <a href="http://self.name">self.name</a></p>
<p>class  Post(models.Model):</p>
<p>title  =  models.CharField(max_length=255)</p>
<p>text  =  models.TextField()</p>
<p>file_name  =  models.CharField(max_length=255, unique=True) # Name of the file</p>
<p>image_name  =  models.CharField(max_length=255) # Name of the image</p>
<p>image_link  =  models.URLField() # Link to the image</p>
<p>def  <strong>str</strong>(self):</p>
<p>return  self.title</p>
<h1 id="advanced-bash-commands--django">ADVANCED BASH COMMANDS &amp; DJANGO</h1>
<h2 id="comando-per-generare-pagine-in-hugo">Comando per generare pagine in Hugo</h2>
<pre><code> #!/bin/bash

  

    # Define paths
    
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
    
    if [ -f  "$new_post_file
</code></pre>

    </div>
  </div>
</body>

</html>
