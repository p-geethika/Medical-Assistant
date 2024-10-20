### Setting up the repository locally

1. First fork the repo :fork_and_knife: to your account.  
   Go to the forked repo and clone it :busts_in_silhouette: to your local machine:

```sh
git clone https://github.com/Your_Username/MedBuddy.git
```

This will make a copy of the code to your local machine.

2. Now move to the `MedBuddy` directory.

```sh
cd MedBuddy
```

3. Now check the remote of your local code by:

```sh
git remote -v
```

The response should look like:

```sh
origin	https://github.com/Your_Username/MedBuddy.git (fetch)
origin	https://github.com/Your_Username/MedBuddy.git (push)
```

To add upstream to remote, run:

```sh
git remote add upstream https://github.com/Aman-Codes/MedBuddy.git
```

Again run `git remote -v`, the response should look like:

```sh
origin	https://github.com/Your_Username/MedBuddy.git (fetch)
origin	https://github.com/Your_Username/MedBuddy.git (push)
upstream	https://github.com/Aman-Codes/MedBuddy (fetch)
upstream	https://github.com/Aman-Codes/MedBuddy (push)
```

4. Once the remote is set, install all the necessary dependencies by the following command:

```sh
npm install
```
### Run locally

Run the below command to start the server:

```sh
npm run dev
```
Go to: [http://localhost:4000](http://localhost:4000)
