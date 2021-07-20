# expense_tracker

The Project: An Expense Tracker

Service for tracking expenses. Customers will use some kind of client software—a com- mand-line app, a GUI, or even a web app—to track and report their daily expenses.

## Major parts of the app:
• A web application written in Sinatra that will receive incoming HTTP requests (to add new expenses or search for existing ones)1
• A database layer using Sequel to store expenses between requests2
• A set of Ruby objects to represent expenses and glue the other pieces together

## Ruby libraries:
gem 'rspec', '3.6.0' 
gem 'coderay', '1.1.1' 
gem 'rack-test', '0.7.0' 
gem 'sinatra', '2.0.0'
