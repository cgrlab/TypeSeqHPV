FROM cgrlab/typeseqhpv:base_190221

WORKDIR /mnt

RUN Rscript -e 'require(devtools); install_github("cgrlab/TypeSeqHPV", ref = "master", force = TRUE)'

#clone repo to get other docs
RUN cd / && git clone --single-branch --branch master https://github.com/cgrlab/TypeSeqHPV.git
