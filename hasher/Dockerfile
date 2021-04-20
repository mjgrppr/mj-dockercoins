FROM ruby
RUN gem install sinatra
RUN gem install thin
COPY hasher.rb .

ENTRYPOINT ["ruby"]
CMD ["hasher.rb"]
# CMD ruby hasher.rb
