## This document describes Moonraker-Telegram's full configuration.

## You can copy all the variables you need to change from here.

### Port of moonraker

```
port="7125"
```

### Your telegram bot token

```
token="your_token"
```

### Your chat ID

```
chatid="your_chatid"
```

### Your moonraker API-Key when u use force login true

```
api_key=""
```

### messages for the states: (for the placeholders in the messages look at https://github.com/Raabi91/moonraker-telegram/blob/master/docs/Variables.md)

### Start message

```
msg_start="Started printing $print_filename"
```

### error/failed message

```
msg_error="printing of $print_filename Failed"
```

### Pause message

```
msg_pause="printing of $print_filename Paused"
```

### Complete message

```
msg_end="Finished printing $print_filename"
```

### Time message

```
msg_state="Printing $print_filename at $print_progress. Current Time $print_current. Remaining Time $print_remaining"
```

### standby message

```
msg_standby="hey, i'm idling, please let me print something"
```

### complete message

```
msg_complete="hey, i finished the last print now i am idling"
```

### paused message

```
msg_paused="hey, i'm on break, please take a look"
```

### error message

```
msg_error="hey, i had a error. please look it up"
```

### bed cool down message

```
msg_bed_cooldown="hey, my heater bed is cool"
```

### time in seconds to get an State update. to disable set it to 0

```
time="0"
```

### Progress in % to get an State update. to disable set it to 0

```
progress="0"
```

### Z Hight in mm to get an State update. to disable set it to 0

```
z_high="0"
```

### Send a cooldown message when a heated bed has cooled to this temperatur. to disable set it to 0

```
bed_cooldown_temperature="0"
```

### activates the images function with pictures = 1, without pictures = 0

```
picture="0"
```

### with these variables you can disable images for individual messages. to disable set to 0

```
pic_start="1"
pic_error="1"
pic_pause="1"
pic_end="1"
pic_state="1"
pic_standby="1"
pic_complete="1"
pic_paused="1"
pic_error="1"
pic_bed_cooldown="1"
```

### with 5sec gif at state message = 1, without gif = 0

```
gif="0"
```

### Select wich cam will genarate your gif. the first cam in the variable will be 1 second cam will be 2 .....

```
gif_cam="1"
```

### your webcam snapshot link

```
webcam="http://127.0.0.1:8080/?action=snapshot"
```
for multicam support look at the faq

### rotate the pic bevor sending, use degrease 0-360

```
rotate="0"
```

### flip the pic horizontally bevor sending, 1 = yes, 0 = No

```
horizontally="0"
```

### flip the pic vertically bevor sending, 1 = yes, 0 = No

```
vertically="0"
```

### Make all commands Disable with 1

```
bot_disable="0"
```

### delay for the Print start Message

```
delay_start_msg="0"
```

### delay for the Print end Message

```
delay_end_msg="0"
```

### Delay for the Pause Message

```
delay_pause_msg="0"
```

## LED Control for Cam

[More detailed description here](https://github.com/Raabi91/moonraker-telegram/blob/master/docs/FAQ.md#How-to-use-automatic-led-for-cam))

### Led on link for picture

```
led_on=""
```

### Led on wait time before picture is taken (in seconds)

```
led_on_delay="0"
```

### Led off link for picture

```
led_off=""
```

### Led off wait time after picture is taken (in seconds)

```
led_off_delay="0"
```