# Java - List Recordings Tutorial

This project serves as a guide to help you build an application with FreeClimb. View this tutorial on [FreeClimb.com](https://docs.freeclimb.com/docs/list-recordings#section-java). Specifically, the project will:

- List the recordings associated with your account

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the Tutorial

1. Configure environment variables.

   | ENV VARIABLE | DESCRIPTION                                                                                                                              |
   | ------------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
   | ACCOUNT_ID   | Account ID which can be found under [API credentials](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard           |
   | API_KEY   | API key which can be found under [API credentials](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard |

## Building and Runnning the Tutorial

1. Build and run the application using command:

   ```bash
   $ gradle build && java -Dserver.port=3000 -jar build/libs/gs-spring-boot-0.1.0.jar
   ```

## Getting Help

If you are experiencing difficulties, [contact support](https://freeclimb.com/support).
