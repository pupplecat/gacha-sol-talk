# Gacha-Sol Talk: Spin the Capsule on Solana! Presentation

## Overview

This repository contains the Slidev presentation for **Gacha-Sol**, a decentralized gacha game built on Solana with a focus on privacy using confidential transfers. The slides were created for a hackathon submission to showcase the project’s motivation, technical implementation, live demo, achievements, and future plans. The presentation highlights how Gacha-Sol leverages Solana’s confidential transfers to ensure private reward distribution, alongside a polished UI and scalable architecture.

- **Live Slides**: [https://pupplecat.github.io/gacha-sol-talk/](https://pupplecat.github.io/gacha-sol-talk/)
- **Gacha-Sol App**: [https://gacha-sol-app.vercel.app/](https://gacha-sol-app.vercel.app/)
- **Contract Address**: `GaChaWso1g5y2Rby6pwLSRxezyoxtbaMDyb5sqwYvNGq` ([devnet](https://explorer.solana.com/address/GaChaWso1g5y2Rby6pwLSRxezyoxtbaMDyb5sqwYvNGq?cluster=devnet))


## Slide Highlights

- **Motivation**: Addressing privacy challenges in gacha games using Solana’s confidential transfers.
- **How It Works**: Users buy pulls with public tokens (e.g., USDC), an authority verifies the vault balance, and rewards are withdrawn confidentially.
- **Tech Stack**: Solana, Anchor 0.31.1, SPL Token 2022, Rust, Next.js, and Tailwind CSS.
- **Achievements**: Unlimited pulls with PDAs, polished UI, and zero-ciphertext proof verification.
- **Future Work**: User-initiated open pull enhancement and mainnet deployment.
- **Live Demo**: Interactive demo showing pull browsing, purchase, and reward reveal.

## Running the Slides Locally

To view or modify the slides locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/pupplecat/gacha-sol-talk.git
   cd gacha-sol-talk
   ```

2. **Install Dependencies**:
   Ensure you have Node.js (v18 or later) installed, then run:
   ```bash
   npm install
   ```

3. **Start Slidev**:
   Launch the Slidev development server:
   ```bash
   npm run dev
   ```
   Open your browser to `http://localhost:3030` to view the slides.

4. **Export to PDF (Optional)**:
   To export the slides as a PDF for submission:
   ```bash
   npm run export
   ```

## Related Projects

- [Gacha-Sol Main Repository](https://github.com/pupplecat/gacha-sol): Source code for the smart contract and app.

## Contributing

Feedback and contributions are welcome! This project is open-sourced under the MIT License. Feel free to fork, submit issues, or create pull requests to improve the presentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Built with [Slidev](https://sli.dev/), a powerful tool for creating presentations with Markdown.
- Thanks to the Solana ecosystem for providing tools like Anchor and SPL Token 2022.
- Inspired by the need for privacy-preserving decentralized applications.