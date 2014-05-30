SI5338-VHDL
===========

VHDL implementation for SiLabs SI5338 Clock Generator with 
ClockBuilder support.


A Python and MATLAB parser for the header file from ClockBuilder is 
available as well as a demo project created with Xilinx ISE 14.4.

Please make sure to regenerate the single port rom
(generated with Xilinx CoreGen) with read depth 512
and write width 24. Use e.g. the attached coe file
(250 MHz clock output) or create with the python or
matlab parser a customized on. Make sure that the coe
file is correctly specified with CoreGen.


Unless otherwise stated, the software on is distributed in the
hope that it will be useful, but WITHOUT ANY WARRANTY; without even the 
implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
THERE IS NO WARRANTY FOR THE SOFTWARE, TO THE EXTENT PERMITTED BY 
APPLICABLE LAW. EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT
HOLDERS PROVIDE THE SOFTWARE "AS IS" WITHOUT WARRANTY OF ANY KIND, 
EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.
THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE SOFTWARE IS 
WITH YOU. SHOULD THE SOFTWARE PROVE DEFECTIVE, YOU ASSUME THE COST OF 
ALL NECESSARY SERVICING, REPAIR OR CORRECTION. IN NO EVENT UNLESS 
REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING WILL ANY COPYRIGHT 
HOLDER, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY GENERAL, SPECIAL, 
INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OR INABILITY 
TO USE THE SOFTWARE (INCLUDING BUT NOT LIMITED TO LOSS OF DATA OR DATA 
BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD PARTIES 
OR A FAILURE OF THE SOFTWARE TO OPERATE WITH ANY OTHER PROGRAMS), EVEN 
IF SUCH HOLDER HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES. 
