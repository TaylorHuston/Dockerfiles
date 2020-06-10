FROM jekyll/jekyll

WORKDIR /home/
RUN git clone https://github.com/TaylorHuston/taylorhuston.github.io.git
RUN chown jekyll:jekyll -R taylorhuston.github.io/
EXPOSE 4000
#RUN cd taylorhuston.github.io/ && bundle install