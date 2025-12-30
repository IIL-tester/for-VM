# for-VM
{
    "$schema": "https://github.com/fastfetch-cli/fastfetch/raw/dev/doc/json_schema.json",
    "logo": {
        "padding": {
            "top": 2
        }
    },
    "display": {
        "separator": " ➜  "
    },
    "modules": [
        "title",
        "separator",
        {
            "type": "os",
            "key": "OS   ",
            "keyColor": "34" // Blue
        },
        {
            "type": "kernel",
            "key": "Ker  ",
            "keyColor": "34"
        },
        {
            "type": "uptime",
            "key": "Up   ",
            "keyColor": "34"
        },
        {
            "type": "packages",
            "key": "Pkg  ",
            "keyColor": "34"
        },
        {
            "type": "shell",
            "key": "Sh   ",
            "keyColor": "34"
        },
        {
            "type": "wm",
            "key": "WM   ",
            "keyColor": "34"
        },
        {
            "type": "terminal",
            "key": "Term ",
            "keyColor": "34"
        },
        {
            "type": "memory",
            "key": "Mem  ",
            "keyColor": "34"
        },
        "break",
        "colors"
    ]
}
