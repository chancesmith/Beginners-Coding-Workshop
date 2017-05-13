# Beautiful pages with CSS
### Beginners Coding Workshop - Stage #2

## slide deck
[https://docs.google.com/presentation/d/1D0ZityRJ7nnBM3glEjirlrTdINdhYLBbV8Y9eLLr3a0/edit#slide=id.gc6f59039d_0_0](https://docs.google.com/presentation/d/1D0ZityRJ7nnBM3glEjirlrTdINdhYLBbV8Y9eLLr3a0/edit#slide=id.gc6f59039d_0_0)

## important to remember
* CSS is not intuitive. So, give it time and welcome to the party.
* CSS goes in order from top to bottom

## selectors
* tag `div` would select all `div`
* class `.cake` would change all elements of `<div class="cake"></div>`
* id `#chocolate` would only select one `<div class="cake" id="chocolate"></div>`

## relational selections
* select `.cake > .layer` would select on the layer in the cake
```

<div class="table">
	<div class="cake">
		<div class="layer">this one</div>
	</div>
	<div class="layer"></div>
</div>

```
* select `.cake + .layer` would select on the layer in the cake
```

<div class="table">
	<div class="cake">
		<div class="layer"></div>
	</div>
	<div class="layer">this one</div>
</div>

```

## CSS game to practice selectors
https://flukeout.github.io/

## Get some practice
Head to CodePen.io