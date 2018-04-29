Get the current session type, text-mode or lightdm+xfce:
Code:
systemctl get-default
Set the current session type to text-mode by disabling lightdm autostart:
Code:
systemctl set-default multi-user.target
Enable lightdm autostart:
Code:
systemctl set-default graphical.target
Works 100% on Kali 2.0.1 + Raspberry PI.
