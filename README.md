# HousingPriceTrend

# Project Overview

This project is a Python application that utilizes the OpenAI and Metaphor API to fetch and answer questions related to various topics, such as recent housing prices in Seattle.
The application generates search queries based on user questions and then summarizes the content of the fetched webpages to provide concise answers.

## Example Output

<img width="1206" alt="Screenshot 2023-10-02 at 5 46 24 AM" src="https://github.com/pcc2k00/HousingPriceTrend/assets/48481860/bc00eb21-79a7-4814-928a-40465322db77">


## Dependencies

- `openai`
- `yaml`
- `metaphor_python`

## Installation

To install the necessary dependencies, run the following command:

```sh
pip install openai pyyaml metaphor-python
```

## Setup
Clone the repository to your local machine.
Create a pass.yml file in the project directory and add your OpenAI and Metaphor API keys as follows:

```
openAi: <Your-OpenAI-API-Key>
metaphor: <Your-Metaphor-API-Key>
```

## Usage
Run the Python script in your preferred development environment.
The script will generate a search query based on the predefined user question, fetch the relevant content using the Metaphor API, and then summarize the content using OpenAI.

## Contributing
Feel free to fork the project, make changes, and submit pull requests. Any contributions are welcome!

## License
This project is open-source and available under <u>the MIT</u> License.

## Contact
For any queries or concerns, please open an issue on this GitHub repository.

## Acknowledgements
- <u>OpenAI</u>
- <u>Metaphor</u>
