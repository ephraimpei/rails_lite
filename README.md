# Using the specs

Some specs have been written to guide you towards the lite :) There are rspec
specs in the `spec` directory and ruby code for you to test with in the `test`
directory.

The specs were written with _you_ in mind ;) Run them in this order they should
generally follow the progression of the project.

## Suggested Order
0.  `bundle exec rspec spec/controller_base_spec.rb`
0.  `bundle exec rspec spec/session_spec.rb`
0.  `bundle exec rspec spec/params_spec.rb`
0.  `bundle exec rspec spec/router_spec.rb`
0.  `bundle exec rspec spec/integration_spec.rb`

Run `bundle exec rspec` to run all the spec files.
