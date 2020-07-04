<h1 align="center">
 AWS Lambda - Minify Images
</h1>

<p align="center">
    This project minifies images to be used in production. It uses a Lambda Function from AWS Service to dispatch the minify function when a new image is created in S3.
</p>

## Development

### `Installing Serverless`
First of all, you have to install the serverless package globally. It's a tool that helps to translate or generalize our configuration to the most important serverless tools in the market as AWS, Google Platform, or Azure.

To install it, you can simple run: `npm install -g serverless`.

### `Setting your servitor credentials into Serverless`

You're going to need to configure your Cloud Server credentials. In this project we used AWS. Then you can run:
`serverless config credentials -o --provider aws --key=your_key --secret your_secret`.

### `Deploying the project`

As it's a Serverless project, most of the job is already done. You just have to run the script `npm run deploy`. 
Then you can use, for example, the AWS CloudWatch to have access to the logs whenever a new image is uploaded in the configurated bucked and path.

## Tecnologies

This project was developed with the following technologies:

- Serverless
- AWS Lambda
- AWS S3

## Social Media

If you want to ask something, please contact me on my social medias.

* **Instagram** - [@pajebr](https://www.instagram.com/pajebr/)
* **Linkedin** -  [josephdsbr](https://www.linkedin.com/in/josephdsbr)
* **GitHub** - [josephdsbr](https://github.com/josephdsbr)

Made with <3 by **José Vinícius**