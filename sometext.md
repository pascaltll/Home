

/sys/class/backlight/intel_backlight

/opt/clion-2021.3.4

4YWW7HXJ74Q2VEN7

2898  sudo systemctl start man-db.service
 2899  sudo mysql_secure_installation
 2900  sudo mariadb
use performance_schema


printbox.io/print

$ conda install scikit-learn-intelex
        $ python -m sklearnex my_application.py
~/.bashrc
 
$ source ~/anaconda3/bin/activate root
$ anaconda-navigator

source ~/.bashrc 
//cahnge language
exec "setxkbmap -layout latam,ru"
exec "setxkbmap -option 'grp:alt_shift_toggle'"

~/.local/bin/bumblebee-status 

sudo brightnessctl -d "intel_backlight" set 50%

# change wallpaper
feh --randomize --bg-fill Pictures/SweetheartAbbey_EN-US7440629451_1920x1080.jpg 

#editor and shower
° less
° glow
° mdview

# protecion de la vision
sudo apt install redshift

# redshift modes
bindsym $mod+r mode "$mode_redshift"
set $mode_redshift Set colour temperature: (a)uto, (r)eset, (2)500K, (3)000K, (4)000K, (5)000K
set $kill_redshift pkill -9 redshift;
mode "$mode_redshift" {
    bindsym a exec --no-startup-id "$kill_redshift redshift -P -t 5000:4000", mode "default"
    bindsym r exec --no-startup-id "$kill_redshift redshift -x", mode "default"
    bindsym 2 exec --no-startup-id "$kill_redshift redshift -P -O 2500", mode "default"
    bindsym 3 exec --no-startup-id "$kill_redshift redshift -P -O 3000", mode "default"
    bindsym 4 exec --no-startup-id "$kill_redshift redshift -P -O 4000", mode "default"
    bindsym 5 exec --no-startup-id "$kill_redshift redshift -P -O 5000", mode "default"
 
    # exit mode: "Enter" or "Escape"
    bindsym Return mode "default"
    bindsym Escape mode "default"
}

jupyter serverextension enable --py jupyter_http_over_ws
jupyter notebook \
  --NotebookApp.allow_origin='https://colab.research.google.com' \
  --port=8888 \
  --NotebookApp.port_retries=0
