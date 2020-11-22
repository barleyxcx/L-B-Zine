# Care Reader
PNCA Graduate Symposium 2020 Care Reader

# BARLEY !!!

## To get started:

- Create folder to work in, open in VS Code
- Terminal > New Terminal
- git clone https://github.com/barleyxcx/L-B-Zine.git
- git init
- git remote add origin https://github.com/barleyxcx/L-B-Zine.git
- git checkout main

## To make changes:
- Open workspace in VS Code
- Terminal > New Terminal
- git fetch (to load any branches added)
- git pull origin main (to bring down any changes made by others
- Make a change in the code, save
- In terminal:
  - git add .
  - git commit -m "description of commit"
  - git pull origin main
  - git push origin main

## Grid system:

Add class="columns" to a container div
Add class="column" to divs inside of that to make evenly spaced columns eg

```
<div class="columns">
    <div class="column first">

    </div>
    <div class="column second">

    </div>
    <div class="column third">

    </div>
</div>
```
for a three-column section.

Add gaps in css with 

```
.column {
    margin: 2%;
}
```

edit a single column with

```
.first {
    font-color:green;
}
```

Peep https://bulma.io/documentation/columns/basics/ for more info
