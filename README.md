# Stk

Stk is a free, real time stock quotes, charts and market overview.

## Background & Motivations

After attending a talk about [Purescript](http://www.purescript.org/) at the Elixir Conf Europe 2017 in Barcelona, I started to read [Purescript by example](https://leanpub.com/purescript/read).
The book is a very good learning material, even though I felt the need to make an application in order to get the grasp
of the language and its ecosystem.

## Roadmap

- [x] v1
  - [x] Display a component with Halogen
  - [x] Fetch an API
  - [x] Parse the JSON
    - [x] by using purescript-foreign
    - [x] by using purescript-foreign-generics
  - [x] Display a lifecycle component and fetch on mount
  - [x] Display a typeahead and send the selection to the parent
  - [x] Display a chart with purescript-echarts
  - [x] Use Bulma CSS framework
  - [x] Use Parcel web application bundler
  - [x] Display multiple types of child component
- [ ] v2
  - [ ] Use local storage to save symbols
  - [ ] Use Signals to update the data
  - [ ] Use purescript-routing
  - [ ] Display market gainers and losers
  - [ ] Display worldwide map with market indexes

## Inspiration & Thanks

* Thanks to [Phil Freeman](https://github.com/paf31), creator of the Purescript language and author of Purescript by Example
* Thanks to [Slamdata](https://github.com/slamdata) for the Halogen type-safe UI library
* Thanks to [Citizennet](https://github.com/citizennet) for the typeahead search component
* Thanks to [IEX](https://iextrading.com/) for providing the data for free
