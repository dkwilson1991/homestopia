# 📚 Not Alone

App for finding homestays as well as hosting your house as a homestay. 

<img width="1293" alt="Screen Shot 2022-12-05 at 11 44 40" src="https://user-images.githubusercontent.com/102286740/205567253-37e141ce-ec65-4dd2-a2b8-d771e1a35108.png">
<img width="1293" alt="Screen Shot 2022-12-05 at 11 44 50" src="https://user-images.githubusercontent.com/102286740/205567268-44de4ce4-fe14-4e8a-af64-3e567f6755af.png">
<img width="1291" alt="Screen Shot 2022-12-05 at 11 45 06" src="https://user-images.githubusercontent.com/102286740/205567283-157ac311-986c-4abd-963c-e92ff1eed9a4.png">
<img width="1293" alt="Screen Shot 2022-12-05 at 11 45 22" src="https://user-images.githubusercontent.com/102286740/205567302-65a9db64-ae0c-486c-814a-3538232ca7ee.png">
<img width="1293" alt="Screen Shot 2022-12-05 at 11 46 30" src="https://user-images.githubusercontent.com/102286740/205567313-56f6f566-548a-432e-a0d4-e18544826fed.png">

## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=cloudinary://482279922763549:5tcC79BwTV8IXG2sBzPxMev7EtE@djnxkxxw9

MAPBOX_API_KEY=pk.eyJ1IjoiZGt3aWxzb24xOTkxIiwiYSI6ImNsYWtmbHhtZjA1Mmgzb3BqNnVvZm9tZ3EifQ.jqERiLo3qGRnI21NTc1YDA
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

<br>

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping


## Team Members
- [Savithri Wewala](https://www.linkedin.com/in/savithri-wewala-507308a1/)
- [Yulia Naumenko](https://www.linkedin.com/in/yulia-naumenko-bba121119/)
- [Ayhem Chelly]()

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
