outdir ?= $(shell rpm --eval '%{_srcrpmdir}')

srpm:
	dnf install obs-service-tools-copr
	obs_copr_build
