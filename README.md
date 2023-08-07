# Symmetrical TF2 CFG
Generally what this CFG does is the following,
* Improves LOD, textures, memory, etc.. for performance
* Reduces unnoticable quality settings
* Add as a drop in replacement, or copy the autoexec.cfg contents to the bottom of your current autoexec.cfg
### Notes
* Tested using Linux only
* Results will vary between systems and configurations
# How to install
Right click TF2 in steam

Navigate to properties, then click browse...

Copy the file to ``tf/cfg``

Add the following launch arguments ``-console -high -novid -nojoy -nosteamcontroller -nohltv -particles 1 -precachefontchars -noquicktime -hushasserts -threads 4096 -random_invariant -noassert -r_emulate_gl -swapcores -glmdisabletrustblit -glmdisabletrustmsaa``

Run TF2
