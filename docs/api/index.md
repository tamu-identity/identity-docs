# Identity API

The API provides a way for client applications across campus to access infrastructure resources in a secure way. The API has the following benefits: 

## Self-service Client Registration

Client applications no longer need to have signed certificates to access the service. Anyone that can log in to CAS can register a client with immediate, though limited, access (public, unsuppressed directory information).

## Synchronous Service Calls

Clients will generally perform a GET and the result of their query will be in the body of the response. 

## Multiple Supported Formats

All services will offer options of either `xml` or `json` response formats.

## General Information

- [Registration](registration.md)
- [Authentication](authentication.md)

## Available Services

- [Directory Search](directory_search.md)
- [Password Status](password_status.md)