CC := gcc
CFLAGS := -g
OBJS=*.o
ODIR=./obj
$(ROOT_DIR)/$(BIN)/$(BIN_APP):$(ODIR)/$(OBJS)
	$(CC) $(CFLAGS) -o $@ $^ -static -lpthread
