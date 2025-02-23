
# Stock Portfolio Analyzer

Stock Portfolio Analyzer is a Streamlit web application. The system extracts text from the uploaded PDF, analyzes the portfolio using Groq API, and provides stock recommendations. The recommendataions inculde which stock to keep, sell and buy along wit suggested qantities.


## Features

- Upload a **portfolio PDF** for analysis.
- Extract stock information from the uploaded file.
- Analyzes the portfolio using Groq API's **Llama-3.3-70B-Versatilie** model.
- Recieve detailed stock recommendataion in **table format**.
- Interactive web-based interface using **streamlit**.


## About Llama

![Llama Overview](https://media.datacamp.com/cms/ad_4nxceo65lqgskpt2gyjdxnyxikzmv_t-3njxvxaqiklpa-hbtvmpmipofzejtrxzdfs2byf_abs10_hfrknvkxzlzxlr0fvtgipmzktuwxhok7awlmun10ox6ahwyou_2r_gyatf4.png)

![Llama 3.3 optimization](https://media.datacamp.com/cms/ad_4nxctfgnmlr5uowmsc3vijkd5ov9i08kietc9ovn2cutrp2ixwt3s_q7dg_fsrjdl6myi37__6elzaf7xxevnaiothxfrjziw454yuxpnwbvdfeadjw-yvhmohoqsfegz4tab0xuq-w.png)
## Requirements

To run the application you need:

- Python 3.x
- Streamlit
- Groq API key
- PyPDF2 for extracting text from PDFs.
## Installation

1. Clone the repository:

```bash
git clone https://github.com/INEcodes/FOSSHack.git
```

2. Install required dependencies:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file and add you Groq API key:

```bash
groq_api = your_api_key_here
```
## Usage

1. Run the Streamlit app:

```bash
streamlit run app.py
```

2. Upload the **PDF** containing your stock portfolio.

3. Wait for the system to extract the text and analyze the portfolio.

4. View stock recommendation in table format.
## Output

- Upload your PDF document

[![image.png](https://i.postimg.cc/bJQkpZKP/image.png)](https://postimg.cc/LY8nV89Q)

- get detailed infomation on your portfolio

[![image.png](https://i.postimg.cc/fRLcmT07/image.png)](https://postimg.cc/ykM3zKjW)
## Limitations

- The quality of analysis depends on the protfolio text extracted from the PDF.

- The API response format should be structured properly for better readability.

- Requires a valid Groq API key for analysis.

## Authors

- [Abhay Singh Chauhan](https://github.com/INEcodes)
- [Abhinav Tiwari](https://github.com/tiwaryfied)
- [Amogh Biradar](https://github.com/RACodes-dev)
- [Dev Deep Narayan](https://github.com/Haiirohito)

