setPosts(prev =>
  prev.map(p => p._id === updated._id ? updated : p)
)
