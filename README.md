# simple-drawerlayout
ps:required jquery

### you can git clone https://github.com/xingobar/simple-drawerlayout.git 

<p>step1: include jQuery:</p>
<pre>
    <code>
        < script type="text/javascript" src="./js/jquery-3.3.1.min.js"/>
    </code>
</pre>

<p>step2. include simple_drawer.css</p>
<pre>
    <code>
        < link rel="stylesheet" href="./scss/simple_drawer.css"/>
    </code>
</pre>

<p>step3: include simple-drawer.js</p>
<pre>
    <code>
        < script type="text/javascript" src="./src/simple-drawer.min.js">
    </code>
</pre>


>>file: index.html
    <div id="simple_drawer_wrapper">
        <header id="simple_drawer_header">
            <button type="button" class="drawer-hamburger"></button>
        </header>
        <nav role="navigation" class="simple-drawer-navigation">
            <ul>
                <li>Option1</li>
                <li>Option2</li>
            </ul>
        </nav>
    </div>
<pre>
    <code>
        simpleDrawer.toggle({
            overlay: boolean, // whether display overlay or not (default true)
            backdrop:string , // set  backdrop color
            guester:string, // set user guester  (click or swipe, default value is click)
        });
    </code>
</pre>