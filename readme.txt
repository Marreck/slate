// Run
docker-compose up

// Build
docker run --rm -v %cd%:/usr/src/app/source -w /usr/src/app/source slate_app bundle exec middleman build --clean