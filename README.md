![](https://github.com/maybe-finance/maybe/assets/35243/79d97b31-7fad-4031-9e83-5005bc1d7fd0)

# Maybe: Open-source personal finance app - Deploy on Railway

This is a minimally modified version of the [Maybe](github.com/maybe-finance/maybe) app that can be deployed on [Railway](https://railway.app).

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/IJfOhC?referralCode=TyiiCX)

You'll need to first create a few values to set up as environment variables, so before getting started you should get the following ready:

-   A [Plaid](https://plaid.com) account
-   A [Postmark](https://postmarkapp.com) account
-   A [Teller](https://teller.io) account
-   A [Polygon](https://polygon.io) account
-   You'll also need to generate two random strings to use as your `NEXTAUTH_SECRET` and `DATABASE_SECRET` environment variables. You can use `openssl rand -base64 32` or [this tool](https://generate-secret.now.sh) to generate them.

Once you have those values, you can click the button above to deploy the app. You'll be prompted to enter the values for each of the environment variables. Once you've entered them, click "Deploy" and Railway will take care of the rest.
