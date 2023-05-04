```ruby
class About
  def enjoys
    # TODO: Add Clojure and Javascript
    %w[ ruby ]
  end

  def works_for
    %w[ Throwpoint WEForum PrimariaS1 ]
  end

  def for_hire?
    works_for.empty?
  end
end
```
