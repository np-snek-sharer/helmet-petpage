# adding a pet
update PETNAME in the two links with the name of the pet
update PET NAME AND DESCRIPTION with whatever you'd like
```
<span>
  <a href="http://www.neopets.com/pound/adopt.phtml?search=PETNAME"><img src="http://pets.neopets.com/cpn/PETNAME/1/5.png"></a>
  <p class="centered-text">PET NAME AND DESCRIPTION</p>
</span>
```
### example:
pet name: senior_froggy

description: senior_froggy loves to eat flies
```
<span>
  <a href="http://www.neopets.com/pound/adopt.phtml?search=senior_froggy"><img src="http://pets.neopets.com/cpn/senior_froggy/1/5.png"></a>
  <p class="centered-text">senior_froggy loves to eat flies</p>
</span>
```
# adding a section
there are two things you need to update when adding a new section
1. the nav section: add `<a href="#ANCHORNAME">SECTION NAME</a>` and update the anchor name and section name
```
<div class="nav" style="position: fixed;">
  <p>JUMP TO SECTION</p>
  <hr>
  <a href="#S1">SECTION 1</a>
  <a href="#S2">SECTION 2</a>
  <a href="#ANCHORNAME">SECTION NAME</a>
</div>
```
2. add a new div section and update the anchor name and section name
```
<div class="row">
  <hr>
  <h2 id="ANCHORNAME">SECTION NAME</h2>
  [section content]
</div>
```
