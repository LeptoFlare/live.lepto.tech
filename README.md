# `live.lepto.tech`
> A stream tool that lets you interact with what I'm working on, through stream.

![License][license-shield]
![Stars][stars-shield]

If you've ever seen me [stream software dev](https://twitch.tv/leptoflare), you will know that you can go to `live.lepto.tech` to see what I'm working on. This repository has the details on how exactly I implement that. If you would like to do it yourself, see the **Running Locally** section.
- Interact and explore the dev build of the website I'm working on.

## Usage <!-- Using the product -->
Go to [`live.lepto.tech`](https://live.lepto.tech).

## Contributing <!-- Using the source -->
1. Fork the repository and clone it.
2. Make a new branch to submit your pull request from.

### Running locally
1. Create a `.env` in the repository root:
   ```yml
   LIVE_PORT=8000
   ```
   Replace `8000` with the port you want to forward.

2. Run `docker-compose up --build` in the repository root.

---

Contact me · [**@LeptoFlare**](https://github.com/LeptoFlare) · [lepto.tech](https://lepto.tech)

As always, distributed under the MIT license. See `LICENSE` for more information.

_[https://github.com/LeptoFlare/live.lepto.tech](https://github.com/LeptoFlare/live.lepto.tech)_

<!-- markdown links & imgs -->
[stars-shield]: https://img.shields.io/github/stars/LeptoFlare/live.lepto.tech.svg?style=social
[license-shield]: https://img.shields.io/github/license/LeptoFlare/live.lepto.tech.svg?style=flat
