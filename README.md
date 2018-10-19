### bloomfilter-rb
---
https://github.com/igrigorik/bloomfilter-rb
```

```

```ruby
require 'bloomfilter-rb'
bf = BloomFilter::Native.new()
bf.insert()
bf.include?()
bf.include?()
bf.delete()
bf.include?()
bf[] = ""
bf[]
bf[]
bf.stats


bf = BloomFilter::Redis.new
bf.insert()
bf.include?()
bf.include?()
bf.delete()
bf.include?()

bf = BloomFilter::CountingRedis.new()
bf.insert()
bf.include?()
sleep()
bf.include?()


```

```

```


