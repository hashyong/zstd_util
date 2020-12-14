# zstd_util
support c++ string, zstd compress，decompress， stream compress, stream decompress

```c++
// if return code not 0 is error
static int CompressString(const std::string& src, std::string& dst, int compressionlevel = DEFAULTCOMPRESSLEVEL);

// if return code not 0 is error
static int DecompressString(const std::string& src, std::string& dst);

// if return code not 0 is error
static int StreamDecompressString(const string& src, string& dst, int compressionlevel = DEFAULTCOMPRESSLEVEL);

// if return code not 0 is error
static int StreamCompressString(const std::string& src, std::string& dst, int compressionlevel = DEFAULTCOMPRESSLEVEL);
```
