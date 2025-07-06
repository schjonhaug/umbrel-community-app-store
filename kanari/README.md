# Schjonhaug's Bitcoin Apps - Umbrel Community App Store

This is a Community App Store for Umbrel containing Bitcoin-related applications.

## Apps

### Kanari
Bitcoin wallet management service with Norwegian SMS notifications.

- **Features**: Create and manage Bitcoin wallets, real-time SMS notifications, transaction analysis
- **Dependencies**: Bitcoin Core, Electrs
- **Port**: 3000

## Installation

1. Add this app store to your Umbrel:
   ```
   https://github.com/schjonhaug/kanari-umbrel-app-store
   ```

2. Install the required dependencies:
   - Bitcoin Core
   - Electrs (Electrum server)

3. Install Kanari from the app store

## Development

To move this to a separate repository:

1. Create a new repository named `kanari-umbrel-app-store`
2. Copy the contents of this `umbrel-app-store` directory to the new repository
3. Update the repository URLs in the configuration files
4. Test the app store with your Umbrel instance

## Support

For issues related to:
- **Kanari app**: https://github.com/schjonhaug/kanari/issues
- **App store**: https://github.com/schjonhaug/kanari-umbrel-app-store/issues