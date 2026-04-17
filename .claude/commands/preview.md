Start the Jekyll preview server for this site.

## Instructions

1. Check if a Jekyll server is already running on port 4000 using `lsof -i :4000`. If one is, tell the user it's already up at http://127.0.0.1:4000 and stop.
2. Otherwise, start the server in the background from the project root:
   ```
   bundle exec jekyll serve --livereload
   ```
3. Wait a few seconds, then verify startup by reading the background process output.
4. Once startup succeeds, tell the user the URL (http://127.0.0.1:4000) and that live-reload is on, so edits to `.md` files auto-refresh.
5. If `bundle install` is needed (e.g., bundler complains about missing gems), run it first, then start the server.
