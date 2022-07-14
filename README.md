# README

# Comando De progrmaacion de proyecto Ruby on rails

# Creacion de Proyecto



# MarketVisual Heroku


# Pasos para habilitar proyecto en local

∑* 
* 
* 

# Usuario Admin
 * 
 * 
 

# Usuario de prueba
* 
* p
# Mailer
* 


### Historias De Usuario 🚀


https://edgeguides.rubyonrails.org/active_storage_overview.html
gem "image_processing", ">= 1.2"
"emmet.includeLanguages": {
        "erb": "html"
    }

pkill -9 -f puma
Comando para git
git init:   inicia git en el proyecto
git add . :a§ade los cabmbio a los derectorios para subirlos
git commit -m "cambios realizados": realiza el comit a los cambios realizados
git push origin maim:  sube los cambios y archivo a los respositorios
git log : commit realizados
git log --oneline: commit realizado en linea 
git branch -m (main para git y master para heroku)

heroku
heroku login: para iniciar secion.
heroku create (nombre) ; crear proyecto en heroku
: subir los cambio y los respositorio
heroku stack:set heroku-18: para cambiar de versio heroku
heroku run rails db:migrate

Cambiar de rama
git branch -M main
git branch -M master

terminal Unbunto bash
ls: muestra los archivo de la carpeta
mkdir: crea carpeta
history : muestra los ultimos comandos


rails
rails generate controller (nonmbres del controlador) (nombre de la pagina)
rails -v: rails version
bundle update


gemset
rvm gemset list: lista gemset
rvm gemset use (nombres gemset):para elegir el gemset
rvm gemset create (nommbre):para crear el gemset
rails new (nombre) -v postgres: crear proyecto con base postgres
bundle install : installar gemas de gemfile
rail new : nuevo proyecto con sqlite
rvm gemset use rails52
clip < ~/.ssh/id_rsa.pub

heroku
curl https://cli-assets.heroku.com/install.sh | sh


gema de error

group :development do
  gem "better_errors"
  gem "binding_of_caller"
end

control + f para buscar dentro del hoja 

otro coamdo heroku para crer archivo
heroku create <name> --stack heroku-18

rails db:migrate reset (no ocupar)

crear el proyecto rail:
rails new blog

crear el modelo de base:
rails g model post title img content

emigrar los datos:
rails db:migrate

controladores solicitados
rails g controller pages index




group :production do
  gem 'pg'
end


 gem 'sqlite3'



gem "devise"
bundle
Divise rails g devise:install

   1. Ensure you have defined default url options in your environments files. Here
     is an example of default_url_options appropriate for a development environment
     in config/environments/development.rb:

       config.action_mailer.default_url_options = { host: 'localhost', port: 3000 }


 3. Ensure you have flash messages in app/views/layouts/application.html.erb.
     For example:

       <p class="notice"><%= notice %></p>
       <p class="alert"><%= alert %></p>

     * Not required for API-only Applications *

 
generar el modelo de divise
ejmplo ;
rails g divise User
rails db:migrate
rails g devise:views

sudo service postgresql start
id = ? 

user_id = current_user 

friend_id = tweet.user_id

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

heroku pg:reset DATABASE_URL --confirm nombreproyecto
Para rellenar la base de datos con sus datos semilla:
heroku run rake db:seed

Puede combinar los dos ˙ltimos ( migrar y inicializar ) en una sola acciÛn ejecutando esto:
$ heroku run rake db:setup


rails g scaffold (modelo) genera un sistema de registros en las tablas que uno le indica .

rails g devise sirve para crear el registro de personas en una pagina

https://tablericons.com/

control d para seleccionar

Todo para instarlar rvm ruby rails
https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-with-rvm-on-ubuntu-20-04

pkill -9 -f puma
extenciones
https://www.youtube.com/watch?v=FJ7K446GyCs

Comando para configuracion ssh
 ssh-keygen -t ed25519 -C "your_email@example.com"

Buscar en la carpeta .ssh clave para agregar equipo en github