<div class="markdown prose w-full break-words dark:prose-invert light">
    <h1>Project: Git and GitHub</h1>
    <p>This project aims to introduce and familiarize you with Git and GitHub, essential tools for any developer. You
        will learn about source code management, creating repositories, writing READMEs, committing, branching, and
        collaborating with others. The project includes resources, learning objectives, requirements, and tasks to
        complete.</p>
    <h2>Summary</h2>
    <p>This project covers the following topics:</p>
    <ul>
        <li>Source code management</li>
        <li>Git and GitHub basics</li>
        <li>Creating repositories and READMEs</li>
        <li>Committing, pushing, and pulling updates</li>
        <li>Branching and merging</li>
        <li>Collaborating with others</li>
        <li>Deciding which files to include or exclude from your repo</li>
    </ul>
    <h2>Tasks</h2>
    <ol>
        <li>Set up your Git and GitHub account</li>
        <li>Create a repository with READMEs</li>
        <li>Write code and create directories and files</li>
        <li>Use branches to isolate work and collaborate</li>
        <li>Keep your repository up to date</li>
        <li>Resolve conflicts between branches</li>
        <li>Create a .gitignore file to exclude specific files</li>
    </ol>
    <h2>Installation</h2>
    <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">$ sudo apt-get update
    $ sudo apt-get upgrade
    $ sudo apt-get install git
    </code></div></div></pre>
    <h2>Basic Usage</h2>
    <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">$ git <span class="hljs-built_in">clone</span> &lt;repo&gt;
    $ <span class="hljs-built_in">touch</span> <span class="hljs-built_in">test</span>
    $ git add <span class="hljs-built_in">test</span>
    $ git commit -m <span class="hljs-string">"Initial commit"</span>
    $ git push origin main
    </code></div></div></pre>
    <h2>Resources</h2>
    <ul>
        <li><a href="https://help.github.com/articles/git-and-github-learning-resources/" target="_new">Resources to
                learn Git</a></li>
        <li><a href="https://help.github.com/articles/about-readmes/" target="_new">About READMEs</a></li>
        <li><a href="https://chris.beams.io/posts/git-commit/" target="_new">How to write a Git commit message</a></li>
        <li><a href="https://learngitbranching.js.org/" target="_new">Learning branching</a></li>
        <li><a href="https://codeinthehole.com/tips/pull-requests-and-other-good-practices-for-teams-using-github/"
                target="_new">Effective pull requests and other good practices for teams using GitHub</a></li>
    </ul>
    <h2>Repository</h2>
    <p>GitHub repository: holbertonschool-zero_day</p>
</div>