# PassTunnel Homebrew tap

```sh
brew trust passtunnel/tap
brew install --cask passtunnel/tap/passtunnel
```

Since Homebrew 6, casks from third-party taps load only once you trust the tap, hence the first line.

[PassTunnel](https://passtunnel.github.io/) is a macOS VPN client (OpenVPN, FortiGate and Cisco AnyConnect) that fills in your one-time codes for you. The app updates itself; `brew upgrade` is not needed. Source: [PassTunnel/passtunnel](https://github.com/PassTunnel/passtunnel).
