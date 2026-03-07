# FXDB MongoDB Connector Plugin

A plugin for [FXDB](https://github.com/thesophisticateddev/fxdb) that adds MongoDB support. Browse databases and collections, view documents in a tree structure, and manage connections.

## Features

- Connect to MongoDB instances with optional authentication
- Browse databases and collections in the sidebar tree
- View documents in an interactive TreeTableView with BSON type highlighting
- Test connection before committing
- Lazy-loading of collections and documents
- Configurable document limit

## Installation

Download the latest JAR from [Releases](https://github.com/thesophisticateddev/fxdb-mongodb-plugin/releases) and place it in `~/.fxdb/plugins/`, or install directly from the FXDB Plugin Manager.

## Building from Source

```bash
mvn clean package
```

The shaded JAR (with MongoDB driver bundled) will be at `target/fxdb-plugin-mongodb-1.0.0.jar`.

## Development

Built with the [FXDB Plugin SDK](https://github.com/thesophisticateddev/fxdb-plugin-sdk). See the SDK README for the full plugin development guide.

## License

MIT
