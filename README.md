# ansible-ios-sim

Install the latest stable [ios-sim](https://github.com/phonegap/ios-sim) via Homebrew.

## Dependencies

* [icopp.homebrew](https://github.com/icopp/ansible-homebrew)
* [icopp.xcode](https://github.com/icopp/ansible-xcode)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.ios-sim
```

## License

MIT
