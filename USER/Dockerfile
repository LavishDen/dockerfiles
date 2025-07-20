FROM almalinux:9
RUN dnf install git -y
RUN useradd lavish

USER lavish
CMD ["google.com"]
CMD ["sleep", "1000"]
ENTRYPOINT ["ping"]