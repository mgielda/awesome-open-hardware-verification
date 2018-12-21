# Open Hardware Verification

*A curated List of Free and Open Source hardware verification tools and frameworks.*

The aim here is to curate a (mostly) comprehensive list of available tools for verifying
the functional correctness of Free and Open Source Hardware designs. The list can
include:
- [Tools](#Tools) which contain or implement verification related functionality
- [Testbench Frameworks](#Frameworks) which make writing testbenches easier
- [Verification Guides](#Guides) and blog posts on how to actually go about verifying a hardware design
- [Conferences](#Conferences) where new work on open source hardware verification is talked about

**Note:** this list focuses on *Verification* and not *design*. While there are lots of cool new
languages and frameworks aimed at making hardware design easier (or at least, *not Verilog/VHDL*),
verification can sometimes get left out in the cold.
While some new design tools/languages make the claim that "our new design tool `X` makes verification
easier because it is written in high level language `Y`", it can often be much harder to see concrete
evidence of this in terms of re-usable verification IP/frameworks/methods which are actually written
in "new language/tool `Y`". It might seem mean, but just being a new design language which 
*theoretically* makes verification easier is not enough to merit inclusion on this list. What's
needed is *practical* demonstration of making verification easier. This can be through libraries or
IP which use "new language/tool `Y`", or in depth tutorials which explain how to use it for proper
design verification.

If you're after hardware *design* tools, these awesome lists are a good place to start:
- [awesome-hdl](https://github.com/drom/awesome-hdl)

---

## Tools:

For each tool entry, the following information should be included:

**Tag** | **Description**
--------|-----------------------------------------------------------------------------
Design Language | Which language(s) does the tool allow you to work with.
Verification Language | Which language(s) does the tool allow you to write your testbench infrastructure in.
License Status | How can the tool be used by others?
Features | What sort of verification functionality is provided by the tool.

### Yosys/Symbiyosys
- TBD

### Verilator
- TBD

## Frameworks:

For each framework entry, the following information should be included:

**Tag** | **Description**
--------|-----------------------------------------------------------------------------
Design Language | Which language(s) does the framework allow you to work with.
Verification Language | Which language(s) does the framework allow you to write your testbench infrastructure in.
Implementation language | Which language(s) is the framework itself implemented in.
License Status | How can the framework be used by others?
Features | What sort of verification functionality does the framework aim to provide?

### Cocotb
- TBD

### riscv-formal
- TBD

### UVVM
- TBD

### OSVVM
- TBD

## Guides:

- TBD

## Conferences:

### ORCONF

*"ORConf is an annual conference for open source digital, semiconductor and embedded systems designers and users. Each year attendees are treated to an ever-impressive array of presentations from all corners of the open source hardware space."*

- Link: https://orconf.org/

### OSDA

*"Workshop on Open Source Design Automation (OSDA)"*

*"This one-day workshop aims to bring together industrial, academic, and hobbyist actors to explore, disseminate, and network over ongoing efforts for open design automation, with a view to enabling unfettered research and development, improving EDA quality, and lowering the barriers and risks to entry for industry. These aims are particularly poignant due to the recent efforts across the European Union (and beyond) that mandate 'open access' for publicly funded research to both published manuscripts as well as any code necessary for reproducing its conclusions."*

- Longer Description: https://osda.gitlab.io/motivation.html
- Link: https://osda.gitlab.io/
