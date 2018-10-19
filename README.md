### bloomfilter-rb
---
https://github.com/igrigorik/bloomfilter-rb
```

```

```ruby
require 'bloomfilter-rb'
bf = BloomFilter::Native.new(:size => 100, :hashes => 2, :seed => 1, :bucket => 3, :raise => false)
bf.insert("test")
bf.include?("test")
bf.include?("blah")
bf.delete("test")
bf.include?("test")
bf["test2"] = "bar"
bf["test2"]
bf["test3"]
bf.stats


bf = BloomFilter::Redis.new
bf.insert('test')
bf.include?('test')
bf.include?('blah')
bf.delete('test')
bf.include?('test')

bf = BloomFilter::CountingRedis.new(:ttl => 2)
bf.insert('test')
bf.include?('test')
sleep(2)
bf.include?('test')


```

```

```


