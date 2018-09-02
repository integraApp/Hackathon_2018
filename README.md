# Hackathon_2018

Grupo C3


ROTAS DA API
```
                          POST   /cards/:id/add_people(.:format)                                                          cards#add_people
                          GET    /cards/:id/add_people(.:format)                                                          cards#add_people
                    ideas GET    /ideas(.:format)                                                                         cards#ideas
                  actions GET    /actions(.:format)                                                                       cards#actions
        card_participants GET    /cards/:card_id/participants(.:format)                                                   participants#index
                          POST   /cards/:card_id/participants(.:format)                                                   participants#create
     new_card_participant GET    /cards/:card_id/participants/new(.:format)                                               participants#new
    edit_card_participant GET    /cards/:card_id/participants/:id/edit(.:format)                                          participants#edit
         card_participant GET    /cards/:card_id/participants/:id(.:format)                                               participants#show
                          PATCH  /cards/:card_id/participants/:id(.:format)                                               participants#update
                          PUT    /cards/:card_id/participants/:id(.:format)                                               participants#update
                          DELETE /cards/:card_id/participants/:id(.:format)                                               participants#destroy
                    cards GET    /cards(.:format)                                                                         cards#index
                          POST   /cards(.:format)                                                                         cards#create
                 new_card GET    /cards/new(.:format)                                                                     cards#new
                edit_card GET    /cards/:id/edit(.:format)                                                                cards#edit
                     card GET    /cards/:id(.:format)                                                                     cards#show
                          PATCH  /cards/:id(.:format)                                                                     cards#update
                          PUT    /cards/:id(.:format)                                                                     cards#update
                          DELETE /cards/:id(.:format)                                                                     cards#destroy
          categories_list GET    /categories/list(.:format)                                                               categories#list
               categories GET    /categories(.:format)                                                                    categories#index
                          POST   /categories(.:format)                                                                    categories#create
             new_category GET    /categories/new(.:format)                                                                categories#new
            edit_category GET    /categories/:id/edit(.:format)                                                           categories#edit
                 category GET    /categories/:id(.:format)                                                                categories#show
                          PATCH  /categories/:id(.:format)                                                                categories#update
                          PUT    /categories/:id(.:format)                                                                categories#update
                          DELETE /categories/:id(.:format)                                                                categories#destroy
                    users GET    /users(.:format)                                                                         users#index
                          POST   /users(.:format)                                                                         users#create
                 new_user GET    /users/new(.:format)                                                                     users#new
                edit_user GET    /users/:id/edit(.:format)                                                                users#edit
                     user GET    /users/:id(.:format)                                                                     users#show
                          PATCH  /users/:id(.:format)                                                                     users#update
                          PUT    /users/:id(.:format)                                                                     users#update
                          DELETE /users/:id(.:format)                                                                     users#destroy
```
