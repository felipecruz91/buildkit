# https://github.com/docker/for-win/issues/5254

FROM hello-world:latest@sha256:62af9efd515a25f84961b70f973a798d2eca956b1b2b026d0a4a63a3b0b6a3f2

ENV A path
ENV B another\\path
ENV C trailing\\backslash\\
ENV D This should not be appended to C
ENV E hello\
\
world
ENV F hello\
 \
world
ENV G hello \
\
world
