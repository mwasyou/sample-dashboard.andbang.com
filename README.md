# And Bang Sample Dashboard

A sample application for building a dashboard for your team to see who's online, what they're working on and what they're finishing. A hosted version is also available at: https://sample-dashboard.andbang.com

Also, be sure to checkout https://developer.andbang.com for all the details on how to get set up to talk to the And Bang API.


## How to run it

1. Make sure you've got node 0.8+, git, and npm installed (npm comes with node these days)

2. clone the repo:

```
git clone git@github.com:andyet/sample-dashboard.andbang.com.git
```

3. cd into the directory and install dependencies

```
cd sample-dashboard.andbang.com
npm install .
```

4. register a new application. 

    1. go to https://accounts.andbang.com/developer
    2. click "register a new app"
    3. Give you app a name and the callback URL should be: http://localhost:3003/auth/andbang/callback

5. From the resulting page enter the values from ID and secret into your `dev_config.json` file at the root of the project.

5. Run the server

```
node server.js
```

6. Open it in your browser at: http://localhost:3003

7. You should now see your team on the dashboard. If not... contact support: support@andbang.com and optionally yell (nicely) at [@HenrikJoreteg](http://twitter.com/henrikjoreteg) or [@andbang](http://twitter.com/andbang) on twitter. <3

## For a full description of how it's put together 

Read the dot net article @HenrikJoreteg wrote on this: 

[part 1](https://github.com/HenrikJoreteg/dot-net-article/blob/master/part1.md) - Introduction and setup

[part 2](https://github.com/HenrikJoreteg/dot-net-article/blob/master/part2.md) - Building the client


## Bugs

Feel free to file them as issues on this repo. Or send pull requests or contact support. Thanks!


## License

MIT


