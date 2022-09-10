# archConfig

Config for Awesome Window Manager

![image](https://user-images.githubusercontent.com/60976631/147830543-cfb78fe5-4d0b-46fb-9b29-0571b9dceab5.png)



# Dmenu 

- XOpenIM failed Error
  its because en_GB.UTF-8 is not enable in [locale](https://wiki.archlinux.org/title/locale)
1. `locale -a`
2. edit **/etc/locale.gen** at the end add `en_GB.UTF-8 UTF-8`
3. `locale-gen && localectl set-locale LC_CTYPE=en_GB.UTF-8`
4. Now it should run 


