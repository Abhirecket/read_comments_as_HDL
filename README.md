# read_comments_as_HDL
 ### RTL Description: "read_comments_as_HDL" Module

- **Engineer**: Abhishek Kumar Kushwaha
- **Date Created**: March 21, 2024
- **Module Name**: read_comments_as_HDL
- **Company**: College of VLSI
- **Revision**: Revision 0.01 - File Created

#### Overview:
This Verilog module `read_comments_as_HDL` demonstrates the usage of synthesis directives within comments to control synthesis tools. Specifically, it toggles the synthesis directive `read_comments_as_HDL` on and off to include or exclude the module from synthesis.

#### Functional Description:
The module defines an AND gate logic using Verilog syntax. However, the module instantiation and logic are commented out using block comments (`/* ... */`). This allows the synthesis directive `read_comments_as_HDL` to control whether the module is synthesized or not. When the directive is enabled, the module is included in synthesis, and when it is disabled, the module is excluded from synthesis.

#### Dependencies:
This RTL design has no external dependencies.

#### Implementation Details:
- **Module Logic**: The module contains an AND gate logic implemented using an assign statement (`assign y = a & b;`). However, the logic is commented out to prevent synthesis unless explicitly enabled by the synthesis directive.
- **Synthesis Directive**: The synthesis directive `read_comments_as_HDL` is used to control whether the module is included in synthesis. When the directive is enabled (`on`), the module is synthesized. When it is disabled (`off`), the module is not synthesized.

#### Target Devices and Tool Versions:
This RTL design does not target specific devices or tool versions. It is intended to demonstrate synthesis directives and their impact on synthesis tools.

#### Additional Comments:
- This RTL design serves as a demonstration of how synthesis directives within comments can be used to control synthesis behavior.
- Synthesis directives provide flexibility in managing synthesis options and can be useful for debugging, optimization, or design exploration purposes.


<h3 align="left">SYNTHESIZED RTL</h3>
<img width="756" alt="image" src="https://github.com/Abhirecket/read_comments_as_HDL/assets/46784291/14b81377-ae38-40c2-b9fa-ca04df7a89ea">

![image](https://github.com/Abhirecket/read_comments_as_HDL/assets/46784291/2aa6de3a-0bd2-4985-8ea2-7f9709b84191)

<h3 align="left">UTILIZATION SUMMARY</h3>
<img width="715" alt="image" src="https://github.com/Abhirecket/read_comments_as_HDL/assets/46784291/feaa1f56-cac3-4ce7-82c4-188cf7f42d88">

<img width="645" alt="image" src="https://github.com/Abhirecket/read_comments_as_HDL/assets/46784291/4207081f-0077-4f25-92c7-6a21262d8f0c">

