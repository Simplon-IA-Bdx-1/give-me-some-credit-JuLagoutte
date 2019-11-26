FROM ageron/handson-ml
USER root
COPY /requirements.txt /tmp/
RUN pip install -r /tmp/requirements.txt
RUN jupyter contrib nbextension install
RUN jupyter nbextension enable --py --sys-prefix qgrid

# Optional: uncomment the extensions you want to enable
#
# RUN jupyter nbextension enable livemdpreview/livemdpreview
# RUN jupyter nbextension enable hinterland/hinterland
# RUN jupyter nbextension enable snippets/main
# RUN jupyter nbextension enable snippets_menu/main
# RUN jupyter nbextension enable toc2/main
