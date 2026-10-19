# PDF_Password_Remover_Flask

The Flask backend powers the separate developer API for
[Unclasp PDF tools](https://pdf-fe-kappa.vercel.app/). The public PDF tools are
available at [pdf-fe-kappa.vercel.app](https://pdf-fe-kappa.vercel.app/); API
usage and server-side processing details are documented on the
[API documentation page](https://pdf-fe-kappa.vercel.app/docs).

### Author

[Sai Krishna Chaitanya](https://pdf-fe-kappa.vercel.app/about) ·
[Personal portfolio](https://mraskchay.vercel.app/) ·
[GitHub](https://github.com/mr-ask-chay) ·
[Linktree](https://linktr.ee/MR_ASK_Chay)

### Live Testing
Access the app at https://flask-pdf-pr-main.onrender.com/



### Installation For runing the project in local machine.

1. Clone the repository: https://github.com/mr-ask-chay/PDF_Password_Remover_Flask.git
2. Install dependencies: pip install -r requirements.txt
3. Start the Flask server: flask run
4. Access the application at http://127.0.0.1:5000

   
### API Endpoints

#### `/remove_password` - POST request to remove the password from a PDF file.

This endpoint allows you to remove the password from an encrypted PDF file. To use this endpoint, follow these steps:

- **HTTP Method:** POST

- **Request Headers:** None required.

- **Request Body:** The request body should be of type `multipart/form-data` and should include the following fields:

  - `password` (Text): The password required to decrypt the PDF file.
  - `pdfFile` (File): The encrypted PDF file you want to remove the password from.

  To send the request using tools like `curl` or Postman, ensure that you select the `multipart/form-data` option and include the `password` and `pdffile` keys accordingly.

## Deploy and Hosted
The flask projected was deployed and hosted on Render

## Contact

If you have any questions or suggestions, please feel free to [contact me](https://linktr.ee/MR_ASK_Chay).
