{
  "hooks": {
    "PreToolUse": [
      {
        "matcher": "Write",
        "hooks": [
          {
            "type": "command",
            "command": "echo 'Writing to a file - be careful!'"
          }
        ]
      }
    ]
  }
}
