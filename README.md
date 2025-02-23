
# Stock Portfolio Analyzer

Stock Portfolio Analyzer is a Streamlit web application. The system extracts text from the uploaded PDF, analyzes the portfolio using Groq API, and provides stock recommendations. The recommendations include which stock to keep, sell and buy along with suggested quantities.


## Features

- Upload a **portfolio PDF** for analysis.
- Extract stock information from the uploaded file.
- Analyzes the portfolio using Groq API's **Llama-3.3-70B-Versatilie** model.
- Receive detailed stock recommendations in **table format**.
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

##  Features

-  **Real-time Portfolio Analysis** – Track and analyze assets with live data.
-  **Investment Insights** – Get detailed reports on gains, losses, and trends.
-  **Multi-Asset Support** – Manage multiple assets in one place.
-  **User-friendly Interface** – Intuitive UI for easy navigation.
-  **Secure & Private** – Ensuring user data privacy.

##  Tech Stack

| Technology       | Purpose                        |
|-----------------|--------------------------------|
| **Next.js**     | Frontend framework            |
| **Tailwind CSS** | UI styling                    |
| **Node.js**     | Backend runtime               |
| **Express.js**  | Backend framework             |
| **MongoDB**     | Database for storing data     |
| **Firebase Auth** | User authentication         |
| **Axios**       | API handling                  |
| **Chart.js**    | Data visualization            |

## Usage

1. Run the Streamlit app:

```bash
streamlit run app.py
```

2. Upload the **PDF** containing your stock portfolio.

3. Wait for the system to extract the text and analyze the portfolio.

4. View stock recommendations in table format.
## Output

- Upload your PDF document

[![image.png](https://i.postimg.cc/bJQkpZKP/image.png)](https://postimg.cc/LY8nV89Q)

- get detailed information on your portfolio

[![image.png](https://i.postimg.cc/fRLcmT07/image.png)](https://postimg.cc/ykM3zKjW)
## Limitations

- The quality of the analysis depends on the portfolio text extracted from the PDF.

- The API response format should be structured properly for better readability.

- Requires a valid Groq API key for analysis.

Made with ❤️ by [Abhay Singh Chauhan](https://github.com/INEcodes) , [Abhinav Tiwari](https://github.com/tiwaryfied) , [Dev Deep Narayan](https://github.com/Haiirohito) , [Amogh Umesh Biradar](https://github.com/RACCodes-dev)

