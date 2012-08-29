# Minegraph

Visualizing Minecraft recipes using [Graphviz](http://www.graphviz.org/)

## About

I'm building this for a few reasons:

* as a vehicle for learning the recipes in Minecraft
* as a a vehicle for learning Graphviz and the DOT format
* to make a pretty chart and discover/visualize the patterns in Minecraft recipes

## Usage

To generate the graph you need to have Graphviz installed.  You can:

* open `crafting.dot` in Graphviz
* run `dot -Tpdf -o minegraph.pdf crafting.dot`
* run `bundle` then `bundle exec guard` to watch `crafting.dot` for changes and automatically generate the PDF

## Credit

Recipe informatin and images from [Minecraft Wiki](http://www.minecraftwiki.net/)

