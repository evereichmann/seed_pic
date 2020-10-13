# SeedPic

This is a gem for seeding your data base with image urls so you can focus on development. 

- SeedPic
    - [Installing](#installing)
    - [Usage](#usage)
        - [Person](#person)
        - [Animal](#animal)
        - [Product](#product)
        - [Landscape](#landscape)
        - [Building](#building)
    - [Contributing](#contributing)
    - [License](#license)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'seed_pic'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install seed_pic

## Usage

### Person

- Groups of people: 


      SeedPic::Person.group

- Families:   
   
  
      SeedPic::Person.family

- Generic Avatar  
   

      SeedPic::Person.avatar

- Outward appearing male individuals  
  
      SeedPic::Person.male

- Outward appearing female individuals       
      
      SeedPic::Person.female

- working on adding nonbianary, would love to have input from contributers 

### Animal

- Cat

        SeedPic::Animal.cat
- Dog

        SeedPic::Animal.dog
- Horse

        SeedPic::Animal.horse
- Fish

        SeedPic::Animal.fish
- Snake

        SeedPic::Animal.snake
- Lizard

        SeedPic::Animal.lizard
- Rodent 

        SeedPic::Animal.rodent
- Bird

        SeedPic::Animal.bird
- Wild Animal

        SeedPic::Animal.wild
- Woodland Animal

        SeedPic::Animal.woodland

### Product

- Clothes

      SeedPic::Product.clothes

- Food 

      SeedPic::Product.food

- Kitchen items 

      SeedPic::Product.kitchen

- Bag

      SeedPic::Product.bag

- Container

      SeedPic::Product.container

- Mechanical

      SeedPic::Product.mechanical

- Tech
 
      SeedPic::Product.tech

- Music

      SeedPic::Product.music


### Landscape

- Season

    - Summer Landscapes

          SeedPic::Landscape.season_landscape
    - Winter Landscapes

          SeedPic::Landscape.season_landscape(1) 
        
    - Spring Landscapes

          SeedPic::Landscape.season_landscape(2)
    - Fall Landscapes

          SeedPic::Landscape.season_landscape(3)
    
- Rural Landscape

        SeedPic::Landscape.rural

- Landscapes with water 

        SeedPic::Landscape.with_water
### Building
- Office

        SeedPic::Building.office_building

- Store front 

        SeedPic::Building.store_building
- City

        SeedPic::Building.city_building
- Rural

        SeedPic::Building.rural_building
- Houses 

        SeedPic::Building.house

- Future Ideas 
    - rooms, coffee shops, bars, library


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/evereichmann/seed_pics. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/evereichmann/seed_pics/blob/master/CODE_OF_CONDUCT.md).


## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the SeedPic project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/evereichmann/seed_pics/blob/master/CODE_OF_CONDUCT.md).
