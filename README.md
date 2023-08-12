# Symmetrical TF2 CFG
Generally what this CFG does is the following,
* Improves LOD, textures, memory, etc.. for performance
* Reduces unnoticable quality settings
* Should not interfere with network settings
* Add as a drop in replacement by renaming one of the above execs to autoexec.cfg or install below
### Notes
* Tested using Linux only
* Results will vary between systems and configurations
* Depending on your system, setting ``threadpool_affinity 1`` may help performance.
* On NVIDIA systems ``gl_amd_occlusion_workaround 0`` may help performance.
# How to install
Right click TF2 in steam

Navigate to properties, then click browse...

Copy the file to ``tf/cfg``

Open ``autoexec.cfg`` and write on the very bottom ``exec symmetrical-balanced``

Add the following launch arguments:

``-console -high -novid -nojoy -nosteamcontroller -nohltv -particles 1 -precachefontchars -noquicktime -hushasserts -threads 6500 -random_invariant -noassert -r_emulate_gl -swapcores -glmdisabletrustblit -glmdisabletrustmsaa``

Run TF2
