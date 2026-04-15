[[def: gleif-api, GLEIF API]]

~ API to directly access the complete LEI data pool in real time with rich query capabilities.

~ QVIs must use the GLEIF API to look up the Entity and Registration Statuses of LEIs, to ensure that vLEI credentials are only issued to organizations who have an LEI in good standing, specifically an Entity Status of Active and an LEI Registration Status of Issued, Pending Transfer or Pending Archival in the Global LEI System. vLEI credentials which do not maintain these Entity and Registration statuses are subject to revocation.

~ [[insert: spec/snippets/vlei-egf-source.md]]
