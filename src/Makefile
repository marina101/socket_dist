EBIN = ../ebin
ERL = erl
GEN = beam
ERLC_EMULATOR = erl -boot start_clean
PATH= .:$(ERLHOME)/bin:/bin:/usr/bin:/usr/local/bin
SOURCE = chat_client.erl \
	chat_group.erl \
	chat_server.erl \
	io_widget.erl \
	mod_chat_controller.erl
TARGETS = $(SOURCE:%.erl=$(EBIN)/%.beam)

CODE = $(SOURCE:%.erl=$(EBIN)/%.beam) 



$(EBIN)/%.beam: %.erl
	erlc  -W -b beam -o $(EBIN) $(EFLAGS) $(WAIT) $<

 

all: $(TARGETS)
 

   
clean:
	\rm -f $(CODE) 


realclean: clean
	\rm -f \.* *~ *\% #*  *.beam