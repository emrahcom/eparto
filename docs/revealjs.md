## reveal.js

#### package

```bash
cd /tmp
wget https://github.com/hakimel/reveal.js/archive/master.zip
unzip master.zip

cd reveal.js-master
cp -arp dist plugin REPO/revealjs/
```

#### run

```bash
cd REPO
python3 -m http.server
```

#### view

`http://localhost:8000`
