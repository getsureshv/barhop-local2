FROM ruby:2.7.5-alpine3.13
ARG RAILS_ENV=production
ENV RAILS_ENV="${RAILS_ENV}"
ENV APP_VERSION=${TAG}
RUN apk update
RUN apk add bash build-base libxml2-dev libxslt-dev postgresql postgresql-dev nodejs vim yarn libc6-compat curl git which wkhtmltopdf ttf-ubuntu-font-family imagemagick
RUN mkdir /app
WORKDIR /app
COPY template-app/Gemfile* ./
RUN gem install bundler -v 2.4.22 && bundle config https://gem.fury.io/engineerai/ nvHuX-OXxLY2OpiQkFVfgnYgd4CszdA
RUN bundle install
COPY template-app/ .
EXPOSE 3000
CMD ["bundle", "exec", "rails", "server", "-b", "0.0.0.0", "-p", "3000"]
