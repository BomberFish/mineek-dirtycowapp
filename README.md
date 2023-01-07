# DirtyCowApp

This is a all-in-one app for tweaks for iOS 16.1.2 and lower. It uses the MacDirtyCow exploit to overwrite files on the filesystem.

## Making your own tweak
Here is a template for the tweaks.json file:
```json
    {
        "tweaks": [
            {
                "name": "Tweak name",
                "description": "Tweak description",
                "actions": [
                    {
                        "file": "file to replace",
                        "data": "base64 encoded data"
                    }
                ],
                "actionType": "replace" // replace, keyedit
            },
            {
                "name": "Tweak name keyedit",
                "description": "Tweak description",
                "actions": [
                    {
                        "file": "file to edit",
                        "data": "key to edit:value it becomes"
                    }
                ],
                "actionType": "keyedit" // replace, keyedit
            }
        ]
    }
```

## Credits

- [haxi0](https://github.com/haxi0) for help with some tweaks ( No folder blur )
- [verygenericname](https://github.com/verygenericname) for help with some tweaks ( Hide the dock )
