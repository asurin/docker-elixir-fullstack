#Docker image for Full-Stack Elixir Testing

### Synopsis
This is a docker image aimed at providing a full-stack testing environment for both classic ExUnit test as well as browser-based testing using a framework such as Wallaby or Hound.

The goal is to keep the environment as light as possible whilst still allowing a fully-fledged Chromium environment with the ability to run an Elixir program and compile assets using WebDriver

### Info

- Image Size: ~350mb
- Base Image: Alpine 3.12

Bundled Software:
- Chromium 84
- Chromedriver 84
- Erlang/OTP 23.0.3
- Node 14.6.0 
- Elixir 1.10.4
