#
# Install javascripts
#

PREFIX = ~/public_html
SituationalAwarenessDir = $(PREFIX)/SituationalAwareness

LEAFLET = leaflet-1.9.4

all:

install:
	install --compare --backup --directory --target-directory=$(SituationalAwarenessDir) -D $(LEAFLET)
	ln -s $(SituationalAwarenessDir)/$(LEAFLET) $(SituationalAwarenessDir)/leaflet
