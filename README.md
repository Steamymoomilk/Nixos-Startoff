README.md
so the purpose of this project is to make nixos more beginner freindly, which yes i know it is kinda aginst the nixos philosphy of build it yourself. but i was once a complete noob once so ehh, i remember transitoning to nixos was very hard from other
distros and nixos has a mountain of a learning curve, i watched tons of videos and read manpages which helped alot. but nixos is such a great OS i want begginers to learn it. this is the only distro that hasnt had any compromises.

also this is my first github project so go easy on me, and if i didnt credit someone correctly please let me know. i love open soured and the people behind nixOS thanks!!

So cheers to nix-Startoff





how to use this repo

1.first off go and get a nixos install image from https://nixos.org/download.html#nix-more and scroll to the very bottom and install nixos-installer-plasma or gnome edition (these dont matter because its just the installer)
2.Secondly install nixos pick whatever DE you want and make sure to allow unfree packages. (these will not matter because the .config we will use later will change your nixos so dont spend to long pondering)
3.let nixos install
4.after install boot into NixOS now we are going to use this repo and do (sudo nautilus) then use the keybind CONTROL L and type or paste /etc/nixos then Press ENTER, you should now be in a folder with nixos.config
Nixos.configuration is you system build file, you now take the .configuration file from the repo and drop it into the folder and overwrite it. then take the file called software.sh and run (sudo chmod +X softwarecenter.sh)
then go to nautlis as superuser (sudo nautilus) and right click on softwarecenter.sh and click prop  this will clear excess entrys in your boot loader and update packages to the latest channel in stable aswell as install nixos software center


Applications nix-startoff has
nixsoftwarecenter-like gnome software but for nixos packages make sure to use .configuration when installing a package if you want to keep it between rebuilds
discord- to chill with the bois
steam- to game with the bois
gnome tweaks- cause stock gnome is kinda cringe not reall but ehh
git- because it should be a default
kate- because i like it more than vim fight me. LOL long live the church of emacs
tor-browser- cause i wanna google stuff without being tracked
neofetch-because ricing
ntfs3g- adds support for ntfs files
nvtop-to see gpu usage
libreoffice-because word is awful
librewolf-hardend firefox
