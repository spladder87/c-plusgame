#C++ Sneek game

<li class="toclevel-1 tocsection-1"><a href="#Topics_Covered"><span class="tocnumber">1</span> <span class="toctext">Topics Covered</span></a>
<ul>
<li class="toclevel-2 tocsection-2"><a href="#C.2B.2B_Language_-_Procedural_Basics"><span class="tocnumber">1.1</span> <span class="toctext">C++ Language - Procedural Basics</span></a></li>
<li class="toclevel-2 tocsection-3"><a href="#C.2B.2B_Language_-_Object_Oriented_Basics"><span class="tocnumber">1.2</span> <span class="toctext">C++ Language - Object Oriented Basics</span></a></li>
<li class="toclevel-2 tocsection-4"><a href="#C.2B.2B_Language_-_Standard_Library"><span class="tocnumber">1.3</span> <span class="toctext">C++ Language - Standard Library</span></a></li>
<li class="toclevel-2 tocsection-5"><a href="#Chili_Framework"><span class="tocnumber">1.4</span> <span class="toctext">Chili Framework</span></a></li>
<li class="toclevel-2 tocsection-6"><a href="#Game_Programming_Concepts"><span class="tocnumber">1.5</span> <span class="toctext">Game Programming Concepts</span></a></li>
<li class="toclevel-2 tocsection-7"><a href="#General_Programming_Techniques"><span class="tocnumber">1.6</span> <span class="toctext">General Programming Techniques</span></a></li>
<li class="toclevel-2 tocsection-8"><a href="#Graphics_Concepts"><span class="tocnumber">1.7</span> <span class="toctext">Graphics Concepts</span></a></li>
<li class="toclevel-2 tocsection-9"><a href="#Math_.2F_Physics_Concepts"><span class="tocnumber">1.8</span> <span class="toctext">Math / Physics Concepts</span></a></li>
<li class="toclevel-2 tocsection-10"><a href="#Other_Skills"><span class="tocnumber">1.9</span> <span class="toctext">Other Skills</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-11"><a href="#History"><span class="tocnumber">2</span> <span class="toctext">History</span></a></li>
<li class="toclevel-1 tocsection-12"><a href="#List_of_Tutorials"><span class="tocnumber">3</span> <span class="toctext">List of Tutorials</span></a></li>
<li class="toclevel-1 tocsection-13"><a href="#Other_Series"><span class="tocnumber">4</span> <span class="toctext">Other Series</span></a></li>
</ul>
</div>

<h2><span class="mw-headline" id="Topics_Covered">Topics Covered</span></h2>
<h3><span class="mw-headline" id="C.2B.2B_Language_-_Procedural_Basics">C++ Language - Procedural Basics</span></h3>
<ul><li>Basic <a href="/index.php?title=Variable" title="Variable">variables</a> (<code>int</code>,<code>bool</code>,<code>float</code>), <code><a href="/index.php?title=Const" title="Const">const</a></code> specifier, <code>auto</code></li>
<li>Type casting (c-style (type) cast)</li>
<li>Basic arithmetic operations (<code>+</code>, <code>-</code>, <code>/</code>, <code>*</code>, <code>%</code>, precedence <code>()</code>, assignment <code>+=</code> etc.,<code>++</code>/<code>--</code> )</li>
<li>Conditionals (<code>if</code>...<code>else</code>, <code>switch</code>...<code>case</code>)</li>
<li>Boolean logic operations (<code>||</code>, <code>&amp;&amp;</code>, <code>!</code>)</li>
<li>Comparisons (<code>&gt;</code>, <code>&lt;</code>, <code>==</code>, <code>&lt;=</code>, <code>&gt;=</code>, <code>!=</code>)</li>
<li>Loops (<code>while</code>, <code>for</code>, <code>do</code>...<code>while</code>, range-based for)</li>
<li>Writing functions / function parameters / return values / overloading functions</li>
<li>References <code>&amp;</code> / pass by reference-vs-pass by value</li>
<li>Arrays <code>[]</code></li>
<li><code>struct</code> (and its difference from <code>class</code>)</li>
<li><code>enum class</code></li>
<li><code>namespace</code> / <code>using</code></li>
<li>Forward declaration of classes to break circular <code>#include</code> cycles</li>
<li>Uniform initialization of classes / structs with <code>{}</code></li></ul>
<h3><span class="mw-headline" id="C.2B.2B_Language_-_Object_Oriented_Basics">C++ Language - Object Oriented Basics</span></h3>
<ul><li>Creating objects, calling member functions</li>
<li>Creating <code>class</code>es, data members, and member functions</li>
<li><code>public</code> / <code>private</code> member access / encapsulation and data hiding</li>
<li><code><a href="/index.php?title=Const" title="Const">const</a></code>/non-mutating member functions</li>
<li>Writing constructors / initializing embedded objects</li>
<li>Default (automatic) constructor / <code>= default</code>;</li>
<li>Delegating constructors</li>
<li><code>static</code> member variables / <code>static constexpr</code> member variables</li>
<li>Nested classes</li>
<li>Forward declaration to break circular dependencies</li>
<li>Implementing operators for classes</li></ul>
<h3><span class="mw-headline" id="C.2B.2B_Language_-_Standard_Library">C++ Language - Standard Library</span></h3>
<ul><li>Rng &lt;random&gt; <code>std::mt19973</code> / uniform_distributions</li>
<li>Utility functions <code>std::min</code> / <code>std::max</code> / <code>std::swap</code></li>
<li>Math functions <code>std::abs</code> / <code>std::sqrt</code></li>
<li>Measuring time <code>&lt;chrono&gt;</code> <code>std::chrono::steady_clock</code> / duration</li>
<li>Assertions <code>&lt;assert.h&gt;</code></li></ul>
<h3><span class="mw-headline" id="Chili_Framework">Chili Framework</span></h3>
<ul><li>Gfx: putpixel/screenwidth/height</li>
<li>Color: getting/setting RGB color components</li>
<li>Mouse/kbd: input (polled and event-driven)</li>
<li>Sound: loading and playing sounds</li></ul>
<h3><span class="mw-headline" id="Game_Programming_Concepts">Game Programming Concepts</span></h3>
<ul><li>Game loop / frame based animation</li>
<li>Grid coordinate systems and mappings</li>
<li>Variable (measured) time step and fixed time step</li>
<li>Basic rectangle collision detection and handling</li></ul>
<h3><span class="mw-headline" id="General_Programming_Techniques">General Programming Techniques</span></h3>
<ul><li>Recursion</li>
<li>Managing a partially-filled array</li>
<li>Mapping a 2D array onto a 1D array</li></ul>
<h3><span class="mw-headline" id="Graphics_Concepts">Graphics Concepts</span></h3>
<ul><li>Compiled sprite</li>
<li>Drawing filled rectangles and filled circles</li>
<li>Drawing beveled graphics</li>
<li>Pulsating color animation effect</li></ul>
<h3><span class="mw-headline" id="Math_.2F_Physics_Concepts">Math / Physics Concepts</span></h3>
<ul><li>Position / velocity / acceleration</li>
<li>Rebounding off of a vertical/horizontal surface</li>
<li>Basic vector math (vector add/sub/scale/length/normalize)</li></ul>
<h3><span class="mw-headline" id="Other_Skills">Other Skills</span></h3>
<ul><li>Basic visual studio IDE usage &amp; navigation</li>
<li>Visual studio debugger</li>
<li>Git + MSVC</li>
<li>Basic understanding of compiler, linker, .h/.cpp files, .lib/.obj files</li>
<li>Using regex find/replace in visual studio</li></ul>
