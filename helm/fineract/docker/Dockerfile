FROM apache/fineract:latest AS fineract

COPY ./entrypoint.sh /entrypoint.sh

RUN chmod 775 /entrypoint.sh

EXPOSE 8443

ENTRYPOINT ["/entrypoint.sh"]
