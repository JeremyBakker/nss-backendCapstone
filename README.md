# Prometheus

Prometheus is a Python application that uses the Django framework, the Natural Language Toolkit, and a SQLite database to correlate corporate earnings reports and linguistic data from quarterly conference call transcripts. I built the tool to test social psychological and linguistic theories on detecting deception in discourse.

Prometheus parses PDFs of conference call transcripts into individual questions and answers. These linguistic units are then saved in a SQLite database for later ingestion by the application. Prometheus also translates TSV files of earnings data into an interactive line graph in D3 and shows ten points of natural language data for CEOs and CFOs: total word count per transcript, median word count per response, proportion of positive words, proportion of negative words, proportion of responses with references to general knowledge, proportion of responses with reference to value for shareholders, proportion of responses with references to value creation, proportion of first person singular pronouns, proportion of first person plural pronouns, and proportion of indefinite pronouns.

Due to copyright restrictions, I cannot host the source data for the conference calls here.

![image](https://user-images.githubusercontent.com/24864800/27399273-d3debd10-5681-11e7-9787-5f83ee3df7a7.png)

![image](https://user-images.githubusercontent.com/24864800/27188677-8e3f7dca-51b4-11e7-93d4-5e4340574c4e.png)

## Table of Contents

- [Background](#background)
- [Usage](#usage)
- [Maintainer](#maintainer)
- [Contribute](#contribute)
- [License](#license)

## Background

Inspired by James W. Pennebaker's [_The Secret Life of Pronouns: What Our Words Say About Us_](https://www.amazon.com/Secret-Life-Pronouns-Words-About/dp/1608194965), I want to determine what linguistic data can predict about a company's value in the US stock market following quarterly conference calls. Prometheus will quantify CEO and CFO patterns of speech in concert with its display of earnings data over time.

## Usage

COMING SOON. . .

I am working to determine how to host the application in a way that respects the copyright restrictions of the conference call data.

## Maintainer

[Jeremy Bakker](https://github.com/JeremyBakker)

## License

[MIT](LICENSE) © Jeremy Bakker
