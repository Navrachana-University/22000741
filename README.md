<h2>📄 Project Title:</h2>
<h2><b>GenZ Lang Compiler</b> - A Custom Programming Language</h2>

<h2>🔧 Description:</h2>
GenZ Lang is a custom-designed programming language inspired by Gen-Z culture, featuring trendy syntax and vibrant keywords. The language blends modern slang with core programming constructs, creating a unique and engaging coding experience while maintaining functionality for basic programming tasks.

<h2>🎯 Key Features:</h2>
•⁠  ⁠<b>Custom Keywords:</b> Uses Gen-Z-inspired keywords such as <code>wassup</code>, <code>rip</code>, <code>drop</code>, <code>spill</code>, <code>fr</code>, <code>nah</code>, <code>grind</code>, <code>tea</code>, <code>slideIn</code>, and <code>#realtalk</code>.<br>
•⁠  ⁠<b>Basic Constructs Supported:</b><br>
    &nbsp;&nbsp;&nbsp;&nbsp;o Variable declarations and assignments (<code>drop</code>).<br>
    &nbsp;&nbsp;&nbsp;&nbsp;o Output printing (<code>spill</code>).<br>
    &nbsp;&nbsp;&nbsp;&nbsp;o Conditional statements (<code>fr...nah</code>).<br>
    &nbsp;&nbsp;&nbsp;&nbsp;o Looping constructs (<code>grind</code>).<br>
    &nbsp;&nbsp;&nbsp;&nbsp;o Function definition and calling (<code>tea</code>, <code>slideIn</code>).<br>
    &nbsp;&nbsp;&nbsp;&nbsp;o Program start and end keywords (<code>wassup</code>, <code>rip</code>).<br>
•⁠  ⁠<b>Simple Syntax and Semantics:</b><br>
    &nbsp;&nbsp;&nbsp;&nbsp;o Supports integer variables, string printing, and basic control flows.<br>
    &nbsp;&nbsp;&nbsp;&nbsp;o Comments using <code>#realtalk</code>.<br>
    &nbsp;&nbsp;&nbsp;&nbsp;o Functions with no parameters and no return type.

<h2>💻 Technical Implementation:</h2>
•⁠  ⁠<b>Lexical Analyzer:</b> Implemented using Flex (<code>genz_flex.l</code>) to tokenize GenZ Lang keywords, identifiers, numbers, operators, and comments.<br>
•⁠  ⁠<b>Parser:</b> Implemented using Bison (<code>genz_bison.y</code>) to parse language constructs and generate Three-Address Code (TAC) as intermediate representation.<br>
•⁠  ⁠<b>Execution Model:</b> The compiler processes input code to produce TAC, which represents the program’s operations for further processing or optimization.

<h2>🔄 Scope:</h2>
<b>GenZ Lang serves as an educational prototype to demonstrate:</b><br>
•⁠  ⁠Lexical and syntax analysis.<br>
•⁠  ⁠Intermediate code generation (TAC).<br>
•⁠  ⁠Symbol table management.<br>
•⁠  ⁠Function handling and control flow.<br>
•⁠  ⁠Integration of Flex and Bison.

<h2>✅ Status:</h2>
The project successfully compiles GenZ Lang code into Three-Address Code, providing a functional demonstration of lexical analysis, parsing, and intermediate code generation.

<h2>🖥 Commands to Run Lex & YACC Program</h2>
<code>
bison -d genz_bison.y<br>
flex genz_flex.l<br>
gcc lex.yy.c genz_bison.tab.c<br>
./a.out < program.genz
</code>

<h1>🙎🏻‍♂️ Made By: Dhvanika Naik 22000741</h1>