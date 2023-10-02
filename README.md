# Hedvig Letters

Hedvig is a Scandinavian insurance company providing a predictable insurance experience for the next generation. Kanon Foundry was tasked to create a family of typefaces in collaboration with their in-house design department as a way to improve the visual experience of the brand. The idéa was for the typeface to reflect Hedvig’s brand philosophy; To embrace the mistakes we make as humans.

The result was the typeface-family Hedvig Letters. It consists of three fonts; two serifs, and one sans.

The serifs; Hedvig Letters Big & Small was designed to balance the punchy and honest copy they use, with the responsibility and comfort they provide when they handle whatever trouble you get yourself or your stuff into.

The serif comes in two optical weights, and are named accordingly to where they are meant to be used; Hedvig Letters Big for the big print, and Small for the finer applications.

Hedvig Letters Standard is the sans style that takes the role of the work-horse typeface in Hedvig’s visual toolbox.

The way we approached the concept was to imagine the letters from a “non-type-designer” point of view. We realized that the optical corrections we usually apply to a typeface are a method of fooling the eye into perceiving certain shapes as balanced or aligned, when in reality — it’s not. In other words, we trick the eye into thinking something is perfect when it’s not.

So to embrace the mistakes, or in this case the imperfections — we decided not to apply this kind of corrections, where the letterforms allowed it. And this resulted in a typeface where some letters have a slightly odd, yet characteristic look that effectively communicates Hedvig’s design philosophy.


## Building the Fonts

First step is to install gftools in a virtual environment —anywhere but preferably in your local clone of the repo, and not in a (i)cloud:

```
$ python3 -m venv env
$ source env/bin/activate
$ pip install gftools
````
For that you need of course to have Python already installed. If you have doubt about how to use a virtual environment and gftools, check this chapter of the Google Fonts Guide: https://googlefonts.github.io/gf-guide/tools.html

Then, you can build the fonts with these commands:

```
$ cd path/to/sources
$ gftools builder sans.yaml
$ gftools builder small.yaml
$ gftools builder big.yaml
````

Make sure you always activate the virtual env beforehand, each time you want to build: `$ source env/bin/activate`

## License

Hedvig Letters is licensed under the SIL Open Font License v1.1, see [OFL.txt](OFL.txt) for details.

## About Author

Kanon Foundry is a digital type foundry established in 2019 by Alexander Örn and Tor Weibull in Malmö, Sweden. We make retail and custom typefaces with an approach based on research and conceptual thinking.
