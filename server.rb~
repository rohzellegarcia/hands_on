require 'sinatra'
require './expense'

expenses = []

get '/' do
	erb :index
end

get '/new' do
	erb :new
end

post '/save' do
	redirect '/'
end

get '/show/:id' do
	erb :show
end
