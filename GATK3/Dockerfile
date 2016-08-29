FROM bd2kbdds/base_image

ADD gatk3/ /usr/local/gatk3/
ADD samtools/ /usr/local/samtools/

ENV GATK3_PATH "/usr/local/gatk3/"
ENV PATH "$GATK3_PATH:/usr/local/samtools/bin:$PATH"

