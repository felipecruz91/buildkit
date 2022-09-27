FROM ubuntu:14.04@sha256:d7a459ecd77ebb09525584f2c3e1bb7f6a2879d90df8a3523c1b899dfc2a226f

RUN apt-get update -qy && apt-get install tmux zsh weechat-curses -y

ADD .weechat /.weechat
ADD .tmux.conf /
RUN echo "export TERM=screen-256color" >/.zshenv

CMD zsh -c weechat
