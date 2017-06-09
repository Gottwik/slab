# slab
slab is a set of simple css stylesheet classes designed to add vertical whitespace to projects.

See compiled version [here](http://www.sassmeister.com/gist/eb20b9ae092b8f4aefe12ee4c54a3584).

## Dependencies
slab uses media queries from bootstrap 4 but these are included for your convenience. Only a sass compiler is needed to make this work.

## Basic slabs
`.slab` - Will create 10px high horizontal stripe of whitespace

`.subslab` - Will create 10px negative space

## Multiple slabs
Multiple slabs go up to 8x

`slab-5x` - will create 50px high horizontal space

`.subslab-5x` - Will create 50px negative space

## Responsive slabs
responsive slabs share bootstrap media breakpoints list, but you can override it before importing slab with this code:

```scss
$grid-breakpoints: (
	xs: 0,
	sm: 544px,
	md: 768px,
	lg: 992px,
	xl: 1280px
);
```

`slab-sm-down` - will create slab only visible on sm screens and down

`subslab-md-up-4x` - will create slab only visible on sm screens and down


## Half-slab
`half-slab` - will create a 5px high whitespace

## Size
Gzipped 1,46kb
