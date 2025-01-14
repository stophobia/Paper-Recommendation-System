<br/>
<p align="center">
  <a href="https://github.com/mcpeixoto/PaperRecomenderSystem">
    <img src="https://images.emojiterra.com/google/noto-emoji/v2.034/512px/1f50e.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Paper Recommendation System</h3>

  <div align="center">
    For keeping your sanity when searching for papers.
    <br/>
    <br/>
    <a>View Demo (In the Future)</as>
    .
    <a href="https://github.com/mcpeixoto/PaperRecomenderSystem/issues">Report Bug</a>
    .
    <a href="https://github.com/mcpeixoto/PaperRecomenderSystem/issues">Request Feature</a>
  </p>
</div>


<div align="center">
  <img src="https://img.shields.io/github/contributors/mcpeixoto/PaperRecomenderSystem?color=dark-green" alt="Contributors"/>
  <img src="https://img.shields.io/github/issues/mcpeixoto/PaperRecomenderSystem" alt="Issues"/>
  <img src="https://img.shields.io/github/license/mcpeixoto/PaperRecomenderSystem" alt="License"/>
  <img src="https://img.shields.io/github/forks/mcpeixoto/PaperRecomenderSystem?style=social" alt="Forks"/>
  <img src="https://img.shields.io/github/stars/mcpeixoto/PaperRecomenderSystem?style=social" alt="Stargazers"/>
</div>



## About The Project

<div align="center">
  <img src="resources/website.gif" width="900" class="center"/>
</div>

## Built With

* [Streamlit](https://streamlit.io/)
* [Facebook's Faiss](https://github.com/facebookresearch/faiss)
* [Sentence Transformers](sentence-transformers/all-mpnet-base-v2)
* [ArXiv dataset](https://www.kaggle.com/Cornell-University/arxiv)

## Getting Started

### Prerequisites

For this project you will need to have installed [Conda](https://docs.conda.io/en/latest/miniconda.html) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) and have a [Kaggle account](https://www.kaggle.com/).

This also requires ~20Gb of RAM to run and a GPU is recommended
### Installation

1. Install the dependencies

```sh
make install
```

This will use the `environment.yml` file and conda to create a new environment with all the required dependencies.

2. (Optional) Download the Faiss index & Data checkpoint
  
```sh
make download_checkpoint
```

3. Update the Index and Dataset
  
(Optional if you did step 2)

This will download the ArXiv dataset from [Kaggle](https://www.kaggle.com/Cornell-University/arxiv) and create/update the Faiss index.

```sh
make update
```

1. Run the following command to start the Streamlit app:

```sh
make run
```

## Usage

For running the aplicattion, after following the installation steps, run the following command:

```sh
make run
```

If you desire to update the ArXiv dataset and the Faiss index, run the following command:

```sh
make update
```

## Roadmap

- [X] Add Taggs to the papers
- [ ] Provide a way to add the paper to Zotero
- [ ] Add button to find similar papers
- [X] Show the categories
- [X] Show the authors
- [X] Provide a preview of the paper
- [ ] Question Answering to papers
- [X] Add "make download_checkpoint"
- [ ] Filter papers by time

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/mcpeixoto/PaperRecomenderSystem/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/mcpeixoto/PaperRecomenderSystem/blob/main/LICENSE.md) for more information.

## Authors

* [**Miguel Caçador Peixoto**](https://github.com/mcpeixoto/) - *Physics Engineering Student*

