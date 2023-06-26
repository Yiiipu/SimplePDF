# SimplePDF
Simple MacOS PDF reader with ChatGPT integrated. You can chat with your local PDF. The returned response can cite the page number to ensure correctness.

## How it works
SimplePDF uses Apple's PDFKit to deal with PDF rendering and open-source [pdfGPT](https://github.com/bhaskatripathi/pdfGPT) to deal with PDF chatting. As a result, it has fast and beautiful rendering, and the response of GPT model can cite the page number to ensure the information you get is correct. Another bonus is you do not need to upload any PDF to those "chatPDF" sites to start chatting. Simply click-open your local files using SimplePDF and everything is there for you.
<img src="Screenshot 2023-06-26 at 3.24.40 PM.png" width="1800">


## How to use
1. Install [this](SimplePDF.dmg) .dmg file. This is a versin noterized by Apple.
2. Click-open the app, and set your OpenAI API key in settings.
3. To open your file, you can either set SimplePDF as a default app for PDFs, or you can right-click the file and select open with SimplePDF.
4. To enable the chatting with PDF function, you need to set up a local server following the guide from [this repo](https://github.com/bhaskatripathi/pdfGPT). It is the well-known pdfGPT. In short, you download the files in that repo with all the dependencies, and run "lc-serve deploy local api" in termminal to start the local server. For M1 mac, please use Conda.
5. Simply type your question in the text field and hit send!


## Updating
This is the first working version. Please feel free to request new features or bug fixes.
