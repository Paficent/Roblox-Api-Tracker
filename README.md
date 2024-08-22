<!-- ABOUT THE PROJECT -->
## About The Project

This repository tracks changes made to Roblox's Web Api Documentation. Repository updates every 15 minutes via GitHub Actions.


<!-- Usage -->
## Usage

You can make use of this project in many different ways, such as:
  - Using the [Roblox-Api-Tracker Website](https://paficent.github.io/Roblox-Api-Tracker) to view all current endpoints by inputting the json url into the top bar.
  - Clicking [here](https://github.com/Paficent/Roblox-Api-Tracker/commits/main/?author=github-actions%5Bbot%5D) to view a list of all tracked API changes.
  - Curling / Requesting the api dump for personal projects.
  - Any other possible method of using this project that you can think of!


<!-- STRUCTURE -->
## Structure
<details>
<summary>A detailed overview of the repository structure</summary>
  
- .github 📁
  - workflows 📁
    - update.yml 📜
      - `The GitHub Actions workflow that automatically updates the repository.`
- example-endpoint 📁
  - `Each folder represents documentation for one endpoint. For example if "example-endpoint" existed, it'd refer to https://example-endpoint.roblox.com/docs`
  - v1.json 📜
    - `Every endpoint has atleast 1 version, many have 2 or even 3. Each version is put into a specific json file and follow the same naming conventions (Version 1 -> "v1")`
- README.md 📕
  - `The file you're currently reading!`
- endpoints.json 📜
  - `All of the endpoints that will be scraped, if Roblox adds a new endpoint feel free to create a pull request with the new endpoint.`
  - `Note: Endpoints need to use OpenApi as a documentation format, or the dumper will not work`

</details>


<!-- CONTRIBUTING -->
## Contributing

All contributions are appreciated, mainly contribute to endpoints.json if a new roblox api is added, or you can contribute to this project's [backend](https://github.com/Paficent/Roblox-Api-Tracker-Backend).

If you have a suggestion that would make Roblox Api Tracker better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give this project a star if you found any use from it!


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [The backend that powers this project](https://github.com/Paficent/Roblox-Api-Tracker-Backend)
* [matthewdean's api list](https://github.com/matthewdean/roblox-web-apis)
