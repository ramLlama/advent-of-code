DAYS := 1

DAYS_TARGETS := $(addprefix build/day,$(DAYS))

all: $(DAYS_TARGETS)

build/%: src/%/main.im
	imlic $(subst main.im,$*.mlb,$<)
