External dependences:
    
    Node
    Yarn:

    Installation steps on Linux (ide.c9.io):
        curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
        echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
        sudo apt-get update && sudo apt-get install yarn

    Installation steps on Mac:
        brew update
        brew install yarn