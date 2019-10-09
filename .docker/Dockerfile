FROM registry.gitlab.com/leonardmessier/shef/shef:1.0.0

ARG USERNAME
COPY ./ /home/${USERNAME}/.config/shef/recipes/main-recipe
WORKDIR /home/${USERNAME}/.config/shef/recipes/main-recipe
RUN make
