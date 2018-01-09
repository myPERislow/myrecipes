Prefix      Verb      URI Pattern        Controller#Action
recipes     GET       /recipes           recipes#index
new_recipe  GET       /recipes/new       recipes#new      #display a new form
            POST      /recipes           recipes#create   #submit the information from the form
edit_recipe GET       /recipes/:id/edit  recipes#edit     #display an edit form
            PATCH     /recipes/:id       recipes#update   #submit the edited form information
recipe      GET       /recipes/:id       recipes#show     #display a particular recipe
            DELETE    /recipes/:id       recipes#destroy  #deletes a particular recipe
