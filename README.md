# CivilityNet

CivilityNet is an advanced system designed to identify and mitigate profane language in conversations, utilizing Long Short-Term Memory (LSTM) for detection and a Sequence-to-Sequence (Seq2Seq) model with an Attention Mechanism for mitigation, pioneering this approach to effectively moderate communication.

## Features

- **Profanity detection**: Uses LSTM to detect offensive language in text.
- **Mitigation mechanism**: Employs Seq2Seq model with Attention to replace offensive words with appropriate alternatives.
- **Handcrafted dataset**: Trained on a custom dataset of approximately 3,200 records.

## Dependencies

- Python 3.10
- pandas
- re
- nltk
- scikit-learn
- tensorflow
- tensorflow-addons
- numpy
- einops
- matplotlib
- tensorflow-text
- gradio

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/PhaniTejaPMSS/civilitynet-profanity-mitigator.git
    ```

2. Change into the project directory:

    ```bash
    cd civilitynet-profanity-mitigator
    ```

3. Install all dependencies:

    ```bash
    pip install pandas re nltk scikit-learn tensorflow tensorflow-addons numpy einops matplotlib tensorflow-text gradio
    ```

## Usage

To use the system, simply run the Jupyter Notebook after installing the necessary libraries and input your text through the Gradio interface. The system will process the text and provide both the detection result and the mitigated text.

## Interface

![CivilityNet](https://github.com/PhaniTejaPMSS/civilitynet-profanity-mitigator/assets/109794469/71a1d7fe-d730-49a8-bbf4-a976e4a17eb0)


## Limitations

Currently, the system works only on CPU and not on GPU. Future updates may aim to include GPU support.

## License

This project is licensed under the MIT License.

## Contact

For any questions or inquiries, please reach out to phanitejacse2021@gmail.com.

