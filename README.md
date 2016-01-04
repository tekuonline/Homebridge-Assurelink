
# Assurelink Plugin (modified form LiftMaster)

Example config.json:

    {
      "accessories": [
        {
          "accessory": "LiftMaster",
          "name": "Garage Door",
          "username": "<your Assurelink email address>",
          "password": "<your Assurelink password>"
        }
      ]
    }

If you have multiple garage doors connected to your Assurelink account, the plugin will print out an error followed by the multiple device IDs it found. You'll need to use these IDs to enter your doors as separate accessories:

    {
      "accessories": [
        {
          "accessory": "LiftMaster",
          "name": "Side Garage Door",
          "username": "<your Assurelink email address>",
          "password": "<your Assurelink password>",
          "deviceID": "<device ID>"
        }
      ]
    }
