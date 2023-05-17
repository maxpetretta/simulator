# Worldcoin Simulator

This is a sample verification app that simulates the behavior of the Worldcoin app to use World ID in the [Test network](https://id.worldcoin.org/test). It works together with World ID's [Javascript Integration](https://docs.worldcoin.org/idkit).

- Generates Sempahore identity for signing World ID requests.
- Persistent Sempahore identities can be generated by signing requests with a real ETH wallet (through WalletConnect interaction).
- Add identity to the tree of verified identities with the identity faucet.
- Interact with World ID's [Javascript Integration](https://docs.worldcoin.org/idkit) to receive verification request, generate ZKP and transfer it back.

<p align="center">
<img src="world-id-mock-app-screenshot-1.png" alt="Screenshot of Worldcoin Simulator" width="700" />
</p>

<p align="center">
<img src="world-id-mock-app-screenshot-2.png" alt="Screenshot of identity faucet" width="700" />
</p>

<!-- WORLD-ID-SHARED-README-TAG:START - Do not remove or modify this section directly -->
<!-- The contents of this file are inserted to all World ID repositories to provide general context on World ID. -->

## <img align="left" width="28" height="28" src="https://raw.githubusercontent.com/worldcoin/world-id-docs/main/public/images/shared-readme/readme-world-id.png" alt="" style="margin-right: 0; padding-right: 4px;" /> About World ID

World ID is the privacy-first identity protocol that brings global proof of personhood to the internet. More on World ID in the [announcement blog post](https://worldcoin.org/blog/announcements/introducing-world-id-and-sdk).

World ID lets you seamlessly integrate authentication into your app that verifies accounts belong to real persons through [Sign in with Worldcoin](https://docs.worldcoin.org/id/sign-in). For additional flexibility and cases where you need extreme privacy, [Anonymous Actions](https://docs.worldcoin.org/id/anonymous-actions) lets you verify users in a way that cannot be tracked across verifications.

Follow the [Quick Start](https://docs.worldcoin.org/quick-start) guide for the easiest way to get started.

## 📄 Documentation

All the technical docs for the Wordcoin SDK, World ID Protocol, examples, guides can be found at https://docs.worldcoin.org/

<a href="https://docs.worldcoin.org">
  <p align="center">
    <picture align="center">
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/worldcoin/world-id-docs/main/public/images/shared-readme/visit-documentation-dark.png" height="50px" />
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/worldcoin/world-id-docs/main/public/images/shared-readme/visit-documentation-light.png" height="50px" />
      <img />
    </picture>
  </p>
</a>

<!-- WORLD-ID-SHARED-README-TAG:END -->

## 🧑‍💻 Development & testing

- Get an Infura project ID from https://infura.io/ and create an `.env` file with it (see [.env.sample](./.env.sample))

- Install dependencies

  ```bash
  yarn
  ```

- Run app locally

  ```bash
  yarn dev
  ```
