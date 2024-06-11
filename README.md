# Cadence NatureDSP Library for MathX 130 DSP cores

<p>This NatureDSP Library for MathX 130 DSP contains various optimized general purpose signal processing routines.</p>

<h1> Version: v2.1.0 </h1>
       <p>This is an early access (v2.1.0) of NatureDSP library for MathX 130 DSP.
This version of library has been tested with RJ-2024.3 Xtensa tools 
and has the same APIs with its predecessor, FloatingPoint KP6.

This release contains following changes when compared to the previous release of FloatingPoint KP6 library v2.0.0:
      </p>
 <h3> Changes:</h3>
       <p>
       <ol>
	   <li>xt-clang LLVM15 migration related changes and fixes</li>
      <li>some extra mips testcases are added
			a) vmatmulnxpnf with P=12 and P multiple of 16
			b) matinv2x2s_f64 L=16, matinv3x3s_f64 L=16</li>
      </ol>
      </p>
<h3> Known issues:</h3>
     <p>
     <ol>
    <li>Performance of some functions may need further tuning for RJ-2024.3 tools</li>
     </ol>
     </p>
<h1> Version: v2.0.0 </h1>
 <h3> Details:</h3>
       <p>
       <ol>
      <li>This version of library has been optimized and tested with RI-2021.8 Xtensa tools.</li>
      </ol>
      </p>
<h3> Known issues:</h3>
     <p>
     <ol>
    <li> None</li>
     </ol>
     </p>



<h1>To use the library </h1>
<p>
<ol>
<li>Download the library & demo xws from the repository and import them into Xtensa Xplorer environment.</li>
<li>Upon importing, two directories i.e. mathx130_library & mathx130_demo  will be available in the Project Xplorer pane.</li>
<li>Refer to Chapter-3 of "NatureDSP_Library_Reference_MathX_130.pdf" document present inside the mathx130_library/doc directory for details on build and run.</li>
<li>Detailed Release notes can be found at mathx130_library/doc directory.</li>
</ol>
</p>



