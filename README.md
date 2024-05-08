# Realtime Birefnet

Welcome to the Realtime Birefnet repository! This repository contains a full model playground for AI image and video generation, specifically supporting Birefnet Background Removal.

## Prerequisites

Before getting started, make sure you have the following prerequisites installed on your machine:

1. [Fal AI](https://www.fal.ai/) API key (for model access)
2. [Node.js](https://github.com/Schniz/fnm)

## Getting Started

To start using the [Birefnet Background Removal](https://fal.ai/models/birefnet) model, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies by running the following command in your terminal:

   ```sh
   npm install
   ```

3. Set up your Fal AI API key by creating a `.env` file in the root directory of the project and adding the following line:

   ```
   FAL_KEY=YOUR_API_KEY
   ```

   Replace `YOUR_API_KEY` with your actual [Fal Key](https://fal.ai/dashboard/keys).

4. Start the development server by running the following command:

   ```sh
   npm run dev
   ```

   This will launch the Realtime Birefnet model playground.

## Usage

Once the development server is running, you can access the model playground by opening your browser and navigating to `http://localhost:3000`.

## Contributing

If you would like to contribute to this project, please follow the guidelines outlined in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Community

If you have any questions or feedback, feel free to reach out to us at [Discord](https://discord.com/invite/Fyc9PwrccF).
