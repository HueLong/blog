FROM elasticsearch:7.10.1

ENV TIMEZONE Asia/Shanghai

#添加分词器
 RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install \
  https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.10.1/elasticsearch-analysis-ik-7.10.1.zip