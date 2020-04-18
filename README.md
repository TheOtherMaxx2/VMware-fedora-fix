# VMware-fedora-fix
Just a script I found and modified to make VMware work on Fedora (unsupported according ton VMware's own website), regardless of the VMware version. Tested for a month and works on Fedora 31 at least. Just get to the right directory via terminal (which would usually be in    

cd /home/[yourfedorasessionusernamehere]/Downloads    

if you just downloaded it here.
Then type   

./fix_vmware_kernel_modules

Hope this works for you as well as it does for me :)

Note: There might be useless stuff in the script. Keep in mind that I've been learning linux's ways for less than 6 months and don't fully know my way around it yet. But this does work for me, and a few friends who tried it, to fix kernel modules update issues. I basically have to run it each time I'm updating Fedora. Perhaps a more permanent solution will come through a crontab or something in the future. Call it unelegant as you wish, but it works.  Max
