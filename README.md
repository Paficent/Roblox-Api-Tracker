<!-- ABOUT THE PROJECT -->
## About The Project

This repository tracks changes made to Roblox's Api Documentation. Repository updates every 15 minutes via GitHub Actions.


<!-- CONTRIBUTING -->
## Contributing

All contributions are appreciated, no matter your skill level, you can also contribute to this project's [backend](https://github.com/Paficent/Roblox-Api-Tracker-Backend)!

If you have a suggestion that would make Roblox Api Tracker better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give this project a star if you found any use from it!


<!-- STRUCTURE -->
## Structure
<details>
<summary>A detailed explanation of the repository structure</summary>
  
- .github 📁
  - workflows 📁
    - update.yml 📜
      - `The GitHub Actions workflow that automatically updates the repository.`
- out 📁
  - example-endpoint 📁
    - `Each folder represents documentation for one endpoint. For example if "example-endpoint" existed, it'd refer to https://example-endpoint.roblox.com/docs`
    - v1.json 📜
      - `Every endpoint has atleast 1 version, many have 2 or even 3. Each version is put into a specific json file and follow the same naming conventions (Version 1 -> "v1")`
- README.md 📕
  - `The file you're currently reading!`
- api.json 📜
  - `Every scraped endpoint and version compiled into one file.`
- endpoints.json 📜
  - `All of the endpoints that will be scraped, if Roblox adds a new endpoint feel free to create a pull request with the new endpoint.`
  - `Note: Endpoints need to use Swagger as a documentation format, or this repository will not work`

</details>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Roblox-Api-Tracker's Backend](https://github.com/Paficent/Roblox-Api-Tracker-Backend)
* [matthewdean's Api List](https://github.com/matthewdean/roblox-web-apis)
