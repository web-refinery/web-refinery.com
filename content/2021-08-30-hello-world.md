+++
title = "Working on my dotfiles and setup scripts."
date = 2021-08-30
+++

For a long time, I've searched for the right tool to set up my machines and configure my tools. 

The past few weeks, I researched various ways to manage my configuration files and setup scripts. I went from a bare git repository for my dotfiles and shell scripts to Ansible. Ansible is sweet, but a bit painful to work with when you're not managing a fleet of machines. It wasn't the right tool for me.

<!-- more -->

I also tried Saltstack. It felt better, more expressive, and it didn't get in my way how Ansible did. Still, it wasn't the right tool.

During my search I came across [NixOS](https://nixos.org) and while I don't particularly enjoy Nix's language, it is the right tool when coupled with home manager. So far, I've got a bare-bones setup that works, and I still have a long way to go before I fully understand Nix's ecosystem. One thing that worries me is that evolutions such as Nix Flakes are really hard to grasps because I don't actually know what problem they intended to solve. Probably because I haven't experienced those problems myself yet and haven't been using Nix long enough. 

All in all, Nix has been the tool I've been looking for. You can track my configurations via [GitHub here](https://github.com/xanderificnl/home).


