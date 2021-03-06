---
layout: default
title: Welcome!
description: This is my site. Welcome.
keywords: github pages, Jekyll, foundation 5
skulpt: true
---

<div class="row">
    <div class="small-12 small-centered column">
    <h1 class="mvl">Python. Client Side.</h1>
        <p>Skulpt is an <em>entirely in-browser</em> implementation of Python.</p>

        <p>No preprocessing, plugins, or server-side support required, just write
            Python and reload.</p>
    </div>

	<div class="medium-11 large-10 small-centered column">
        <div id="quickdocs" style="display: none">
            <ul>
                <li>cut/copy/paste/undo/redo with the usual shortcut keys</li>
                <li>Tab does decent indenting.
                    Thanks to <a href="http://codemirror.net/"
                                 target="_blank">CodeMirror</a> for the text editor.
                </li>
                <li>Ctrl-Enter to run, Shift-Enter to run selected</li>
                <!--
                <li>F9 to toggle breakpoints</li>
                <li>F10 to step over</li>
                <li>F11 to step in</li>
                <li>Shift-F11 to step out.</li>
                <li>You can inspect values with e.g. 'print foo' in the
                &quot;Interactive&quot; box. When debugging, this will
                execute in the debug context.</li>
                -->
            </ul>
        </div>
      </div>
</div>
<div class="row">
    <div class="large-6 small-12 columns">
    <textarea id="code" cols="85" rows="25">
import turtle

t = turtle.Turtle()

for c in ['red', 'green', 'yellow', 'blue']:
    t.color(c)
    t.forward(75)
    t.left(90)
    </textarea>
    <p>
    <button id="skulpt_run">Run</button>
    <a id="toggledocs" href="#">Help</a>, or examples:
        <a href="#" id="codeexample1">1</a>
        <a href="#" id="codeexample2">2</a>
        <a href="#" id="codeexample3">3</a>
        <a href="#" id="codeexample4">4</a>
        <a href="#" id="codeexample5">5</a>
        <a href="#" id="codeexample6">6</a>
        <a href="#" id="codeexample7">7</a>
        <a href="#" id="codeexample8">8</a>.
        Ctrl-Enter to run.
        </p>
    </div>
    <div class="large-6 small-12 columns">
        <div id="mycanvas" height="400" width="400"
                style="border-style: solid;"></div>
        <p><button id="clearoutput">Clear</button></p>
        <pre id="edoutput"></pre>
        </div>

</div>
<div class="row">
<div class="small-12 columns">
    <p>The code is run entirely in your browser, so don't feel
    obligated to &quot;crash the server&quot;, you'll only stub your
    toe. 
    </p>
    <h2>Interactive:</h2>
    <p>This is a very cool new feature that is just getting off the ground.  This would be a great project to jump in and help out on!</p>

    <textarea id="interactive" cols="85" rows="1"></textarea>


    <h2>Your Very Own Copy</h2>

    <p>Want to give it a shot? Grab it with git:</p>
    <pre>
        git clone https://github.com/skulpt/skulpt.git
    </pre>
    <p>
        Or download it like this: <a href="/static/dist/skulpt-latest.tar.gz">skulpt-latest.tar.gz</a> or like this: <a href="/static/dist/skulpt-latest.zip">skulpt-latest.zip</a>
    </p>


    <h2>What's New?</h2>
    <p>
        <ul>
            <li>Suspensions!  This may not mean a lot to you, but trust me its going to be big.  Suspensions provide the foundation for the asynchronous execution we need to build an interactive debugger, a smoother turtle module, enhanced urllib and other cool features.  For developers you should check out the time module and the suspensions.txt file under doc/.</li>
            <li>Stub implementations of the standard library modules. You will now get an unimplemented exceptions rather than some other file not found error.</li>
            <li>General cleanup and standardization of the code.  See the short description of the coding standards in the CONTRIBUTING file</li>
            <li>Loads of bugfixes: <a href="https://github.com/skulpt/skulpt/compare/0.9.2...0.9.4">see</a></li>
            <li><span style='font-family: "Consolas","Lucida Console","Monaco",monospace;'>slice()</span> function implemented. And improvements to list slicing.</li>
            <li><span style='font-family: "Consolas","Lucida Console","Monaco",monospace;'>string</span> and <span style='font-family: "Consolas","Lucida Console","Monaco",monospace;'>operator</span> module added.</li>
            <li>Keyword arguments for <span style='font-family: "Consolas","Lucida Console","Monaco",monospace;'>sorted()</span></li>
            <li><span style='font-family: "Consolas","Lucida Console","Monaco",monospace;'>text()</span> function in processing</li>
        </ul>
    </p>
    <p>By these awesome people:
            <a href="https://github.com/bnmnetp">Brad Miller</a>,
            <a href="https://github.com/rixner">Scott Rixner</a>,
            <a href="https://github.com/albertjan">Albert-Jan Nijburg</a>,
            <a href="https://github.com/mchat">Marie Chatfield</a>,
            <a href="https://github.com/isaacdontjelindell">Isaac Dontje Lindell</a>,
            <a href="https://github.com/jaspervdg">jaspervdg</a>,
            <a href="https://github.com/Lalaland">Ethan Steinberg</a>,
            <a href="https://github.com/Jeff-Tian">Jeff-Tian</a>,
            <a href="https://github.com/meredydd">Meredydd Luff</a> and
            <a href="https://github.com/LeszekSwirski">Leszek Swirski</a>
        </p>

    <h2>Skulpt in the Wild</h2>
    <p>
        <ul>
            <li><a href="http://interactivepython.org/courselib/static/thinkcspy/index.html"> How to Think like a Computer
                Scientist: Interactive Edition</a></li>
            <li><a href="http://interactivepython.org/courselib/static/pythonds/index.html"> Problem Solving with Algorithms
                and Data Structures using Python</a></li>
            <li><a href="http://www.pythonlearn.com/">PythonLearn</a></li>
            <li><a href="https://online.dr-chuck.com/">Dr. Chuck Online</a></li>
            <li><a href="http://www.codeskulptor.org">CodeSkulptor</a></li>
            <li><a href="https://trinket.io/">trinket</a></li>
            <li><a href="http://www.geometryzen.org">Geometry Zen</a></li>
            <li><a href="http://www.evaluzio.net">Evaluzio</a></li>
        </ul>
    </p>
    <p>If you have a project that uses skulpt and would like me to link to it here, let me know on our github page.</p>

    <h2>Skulpt on <a href="http://www.coursera.org">Coursera</a></h2>
    <p>
        <ul>
            <li><a href="https://www.coursera.org/course/interactivepython">An Introduction to Interactive Programming in Python</a></li>
            <li><a href="https://www.coursera.org/course/pythonlearn">Programming for Everybody</a></li>
        </ul>
    </p>

    <h2>Getting Started</h2>

    <p>If you want to embed a nice looking bit of code that your users can edit, Trinket.io can
    help you with that!  You can put together the example on their site, and then generate the
    code for an iframe that you can embed in your page!</p>

    <iframe src="https://trinket.io/embed/python/538012d3a6554c7945027aab" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>


    <p>If you want to roll your own page, Getting started with skulpt on your own page can seem a little intimidating, but here's a really simple example that
    gets you going. You can copy and paste or grab the code from <a href="https://gist.github.com/4650616">this gist</a>.</p>

    <script src="https://gist.github.com/bnmnetp/4650616.js"></script>

    <h2>Helping out!</h2>

    <p>Skulpt surely isn't done yet.</p>

    <p>If you want to check out a list of bugs, or add to it, or see what's been
        fixed recently, you can head over to the always-euphemistic-sounding <a
                href="http://github.com/skulpt/skulpt/issues">issues page</a>.</p>

    <p>If you are interested in contributing to skulpt in any way, check out this new <a href="https://github.com/skulpt/skulpt/blob/master/CONTRIBUTING.md">how to contribute</a> document.</p>

    <p>If you'd like to chit-chat, <a href="http://groups.google.com/group/skulpt">there's a list for
        that</a>.</p>

    <p>And, if &quot;daring&quot; is your <em>middle</em> name, there's a wee bit of <a
            href="static/developer.html">developer docs</a> (New and Improved!).</p>

    <h2>Third Party Modules</h2>
    This new feature lets you create and host your own modules for use in Skulpt.  The
    following gist shows how to include one of them in a page.

    <script src="https://gist.github.com/bnmnetp/20bd9105f11f2a164fc0.js"></script>

    <h2>Customizing modules after import</h2>
    <p>If you want to customize how a module behaves you can use the ``onAfterImport`` hook.  Here is a gist of how the trinket guys do it.</p>
    <script src="https://gist.github.com/bzwheeler/8a5a833ee2a6a7d2c7ba.js"></script>

    <h2>License</h2>

    <p>Skulpt may be licensed under:</p>
    <ol>
        <li>The <a href="http://www.opensource.org/licenses/mit-license.php">MIT license</a>.</li>
        <li>Or, for compatibility with Python, the <a
                href="http://www.opensource.org/licenses/PythonSoftFoundation.php">PSFLv2</a>.
        </li>
    </ol>

    <p> Please note that this dual license only applies to the part of Skulpt that
        is included in the runtime, and not necessarily to surrounding code for build
        processing or testing. Tests are run using <a
                href="http://code.google.com/p/v8/">V8</a>, and <a
                href="http://code.google.com/closure/compiler/">Closure Compiler</a>, and
        some test code is taken from the <a href="http://www.tinypy.org/">tinypy</a>
        and <a href="http://www.python.org/">Python</a> test suites, which may be
        distributed under different licensing terms. </p>

    <h2>About</h2>

    <p>The Father of skulpt is Scott Graham, you can find his blog here: <a href="http://www.h4ck3r.net/">personal page
        (and blog)</a></p>

    <p>My own personal page and blog is <a href="http://reputablejournal.com">Reputable Journal</a></p>

    </div>
</div>

<div class="footer">

    <p>
        Yes, I know how &quot;sculpt&quot; is spelled. The correct spelling was
        thoroughly reserved according to ICANN and search engines.
    </p>

</div>