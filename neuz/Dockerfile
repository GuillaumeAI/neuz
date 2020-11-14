FROM alexjc/neural-enhance


# Install requirements before copying project files
WORKDIR /ne

RUN wget -q "https://github.com/alexjc/neural-enhance/releases/download/v0.3/ne2x-photo-repair-0.3.pkl.bz2"
RUN wget -q "https://github.com/alexjc/neural-enhance/releases/download/v0.3/ne4x-photo-repair-0.3.pkl.bz2"

RUN ls .
RUN pwd
# Set an entrypoint to the main enhance.py script
#ENTRYPOINT ["/opt/conda/bin/python3.5", "enhance.py", "--device=cpu"]
