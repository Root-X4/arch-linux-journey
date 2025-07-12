# 🐧 My Arch Linux Journey

Welcome to my personal documentation of using and customizing Arch Linux. As a cybersecurity student with a focus on offensive security, I chose Arch Linux to better understand the inner workings of Linux and gain full control over my environment.

---

## 💡 Why I Chose Arch Linux

I picked Arch Linux because I wanted to explore:

- *Complete system control*
- *High customizability*
- *In-depth understanding of Linux internals*

Since I'm still relatively new to Linux, I believed that using Arch would accelerate my learning curve and give me hands-on experience in building and maintaining a system from scratch.

To avoid compromising my host machine, I *intentionally installed Arch Linux inside a VirtualBox VM*. This gave me:
- A safe environment to experiment
- The ability to take snapshots and roll back if anything broke
- Protection from potentially malicious scripts or mistakes during setup

This decision also allowed me to test and simulate offensive tools in a secure, isolated setup.

---

## ⚙ My Arch Linux Setup

Here’s a breakdown of the components I used to customize my Arch Linux environment:

| Component         | Tool/Package          |
|------------------|-----------------------|
| Display Protocol | Wayland               |
| Window Manager   | Hyprland              |
| Terminal         | foot                  |
| Bar/Panel        | waybar                |
| Font             | ttf-dejavu, otf-font-awesome |
| Wallpaper Tool   | hyprpaper             |
| AUR Helper       | yay                   |

I chose *Hyprland* as my window manager because it's one of the most popular and actively developed Wayland compositors among Arch users. It offers a clean, dynamic, and highly customizable experience.

The terminal emulator I used is *foot*, which is lightweight, fast, and works well with Wayland environments.

To handle wallpaper management, I used *hyprpaper, and for a status bar, I set up **waybar* with modules to monitor system resources and provide useful information.

---

## 🧠 Lessons Learned

One of the key things I learned through this experience was how to deeply customize my terminal emulator.

I successfully modified the *foot terminal* to match the look and feel of the *Catppuccin* theme, aligning colors, fonts, and behavior with the rest of my Hyprland-based environment.

This hands-on customization taught me:
- How to edit config files for visual and functional changes
- How themes like Catppuccin integrate across tools
- The importance of consistent UI/UX when working in a minimal Linux setup

This process improved both my understanding of *dotfiles management* and my confidence in using *Wayland-native* applications.

---

## 🔐 Cybersecurity Tools (Coming Soon)

Since I'm still exploring and learning the Arch Linux ecosystem, I have not yet installed any offensive security tools. My current focus is on mastering the system itself — from configuration to customization — before building it into a full red team environment.

Once I feel confident with the base system, I plan to install and configure tools like:
- Nmap
- Metasploit
- SQLmap
- Burp Suite
- Wireshark
- And more...

---

## 📸 Screenshots

Here’s a screenshot of my current setup:

![Hyprland + foot + Catppuccin](./screenshots/arch-linux-setup.jpg)  
Customized Arch Linux environment using Hyprland and the Catppuccin theme inside VirtualBox.

---

## 💬 Final Thoughts

Using Arch Linux has been a powerful learning experience. Installing everything from scratch and building a personalized environment using Hyprland helped me better understand how Linux works under the hood. I’m excited to continue expanding this setup and eventually turn it into my main lab for offensive security work.

---

## 🔗 Connect with Me

- LinkedIn: rayyan-n-al-shahrani-72704b292  
- GitHub: [Root-X4](https://github.com/Root-X4)  
- TryHackMe: Finished 70+ rooms (Offensive focus)
