# Resources
## Scripts and tools
* CCL's Python library for LevelDb, IndexedDB, WebStorage, etc. https://github.com/cclgroupltd/ccl_chrome_indexeddb
* Hindsight: https://github.com/obsidianforensics/hindsight
* cLeapp: https://github.com/markmckinnon/cLeapp
* Unfurl: https://dfir.blog/unfurl
* Nirsoft Cookies View: https://www.nirsoft.net/utils/chrome_cookies_view.html

## LevelDB
* Blog describing the format: https://www.cclsolutionsgroup.com/post/hang-on-thats-not-sqlite-chrome-electron-and-leveldb
* Official documentation of the format: 
  * https://github.com/google/leveldb/blob/master/doc/table_format.md
  * https://github.com/google/leveldb/blob/master/doc/log_format.md
* Blog detailing another notable leveldb artefact: https://www.cclsolutionsgroup.com/post/fcm-queued-messages-on-android 

## IndexedDB
* IndexedDB Specification: https://w3c.github.io/IndexedDB/
* Blog covering the format in Chromium: https://www.cclsolutionsgroup.com/post/indexeddb-on-chromium
* Source code links related to the LevelDB database layout:
  * https://github.com/chromium/chromium/blob/master/content/browser/indexed_db/docs/leveldb_coding_scheme.md
  * https://github.com/chromium/chromium/blob/master/content/browser/indexed_db/indexed_db_leveldb_coding.h
  * https://github.com/chromium/chromium/blob/master/content/browser/indexed_db/indexed_db_leveldb_coding.cc
* Source code links related to the key structure: https://github.com/chromium/chromium/blob/master/content/browser/indexed_db/indexed_db_leveldb_coding.cc
* Source code links related to the record structure:
  * https://github.com/v8/v8/blob/master/src/objects/value-serializer.cc
  * https://chromium.googlesource.com/chromium/src/third_party/+/master/blink/renderer/bindings/core/v8/serialization/serialization_tag.h
  * https://chromium.googlesource.com/chromium/src/third_party/+/master/blink/renderer/bindings/core/v8/serialization/v8_script_value_deserializer.h
  * https://chromium.googlesource.com/chromium/src/third_party/+/master/blink/renderer/bindings/core/v8/serialization/v8_script_value_deserializer.cc
* Source code links related to the external data structures: https://github.com/chromium/chromium/blob/master/content/browser/indexed_db/indexed_db_backing_store.cc

## Webstorage
* WebStorage Specification: https://html.spec.whatwg.org/multipage/webstorage.html#webstorage
* Blog explaining the formats in detail: https://www.cclsolutionsgroup.com/post/chromium-session-storage-and-local-storage
* Source code relating to these artefacts: https://source.chromium.org/chromium/chromium/src/+/main:components/services/storage/dom_storage/

## Cache
* Description of the formats: https://source.chromium.org/chromium/chromium/src/+/main:net/disk_cache/README.md
* Source code relating to these artefacts:
  * https://source.chromium.org/chromium/chromium/src/+/main:net/disk_cache/blockfile/disk_format.h
  * https://source.chromium.org/chromium/chromium/src/+/main:net/disk_cache/blockfile/addr.h 
  * https://source.chromium.org/chromium/chromium/src/+/main:net/disk_cache/blockfile/disk_format_base.h 
  * https://source.chromium.org/chromium/chromium/src/+/main:net/http/http_response_info.cc 
  * https://source.chromium.org/chromium/chromium/src/+/main:net/http/http_response_info.h 
  * https://source.chromium.org/chromium/chromium/src/+/main:net/disk_cache/simple/simple_entry_format.h 

## Shared Proto DB
* Source code link to show the key prefixes in shared_proto_db: https://source.chromium.org/chromium/chromium/src/+/main:components/leveldb_proto/public/shared_proto_database_client_list.h 
* Proto file for downloads in shared_proto_db: https://source.chromium.org/chromium/chromium/src/+/main:components/download/database/proto/download_entry.proto


