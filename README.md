# rpc

discord rpc for disocrd account

buttons optional , with status and details




# Installation

- open vsc , or terminal
    . type ```git clone https://github.com/mar1nara/rpc```

- Add assets(image) to your application

- Select images and clear all fields except PARTY ID and JOIN SECRET

- Now go to example.py, put your client id, and change the activity code according to your best fit
    .```activity = {
            "state": "Adobe",  # anything you like
            "details": "Editing",  # anything you like
            "timestamps": {
                "start": start_time
            },
            "assets": {
                "small_text": "Adobe",  # anything you like
                "small_image": "adobe",  # must match the image key
                "large_text": "Illustrator",  # anything you like
                "large_image": "illustrator"  # must match the image key
            }
        }```
