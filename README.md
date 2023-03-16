# cowsay-API

Exactly what it sounds like 🐮💬

Test by running:

    curl https://cowsay-api.herokuapp.com/say -H 'Content-Type: application/json' -d '{"message": "Cow-pilled and moo-core", "cow": "stegosaurus", "balloon_type": "think"}' | ruby -r json -e "print JSON.parse(STDIN.read)['message']"

More details to come!
