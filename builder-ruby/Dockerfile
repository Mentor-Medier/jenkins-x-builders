FROM gcr.io/jenkinsxio/builder-rubybase:0.0.83

# jx
ENV JX_VERSION 2.1.71
RUN curl -f -L https://github.com/jenkins-x/jx/releases/download/v${JX_VERSION}/jx-linux-amd64.tar.gz | tar xzv && \
  mv jx /usr/bin/
