EXTRA_DIST += $(wildcard doc/*.rst)

EXTRA_DIST += \
  doc/conf.py \
  doc/mongoc/__init__.py \
  doc/mongoc-theme/globaltoc.html \
  doc/mongoc-theme/layout.html \
  doc/mongoc-theme/static/mongoc.css_t \
  doc/mongoc-theme/static/pygments.css \
  doc/mongoc-theme/theme.conf \
  doc/taglist.py \
  $(wildcard doc/includes/*.txt)

dist-hook: man html

clean-local:
	-rm -rf doc/man/.buildinfo doc/man/.doctrees
	-rm -rf doc/html/.buildinfo doc/html/.doctrees doc/html/_static
