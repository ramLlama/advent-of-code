all:
	$(error Specify a target with dayX)

build/%: src/%/main.im
	imlic $(subst main.im,$*.mlb,$<)

.PHONY: %
%: build/%
	build/$* src/$*/input
