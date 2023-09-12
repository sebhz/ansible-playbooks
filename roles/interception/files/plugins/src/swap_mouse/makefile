INSTALL_DIR=/usr/local/stow/interception-tools/bin

.PHONY: install clean

swap_mouse: swap_mouse.o

install: swap_mouse
	install -m 755 $< $(INSTALL_DIR)

clean:
	rm -f *.o swap_mouse
