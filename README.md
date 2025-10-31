: Enable verbose output for specified action\n
ucupdate -q
: Query CPU signatures and microcode revisions
ucupdate -i <filename.pdb>
: Display information about microcode file
ucupdate -c <filename.pdb>
: Check whether microcode would apply, but don't update
ucupdate -u <filename.pdb>
: Update CPUs with binary microcode
ucupdate -d <directory>
: Apply the first matching microcode in the specified directory
ucupdate -m <microcode.dat>
