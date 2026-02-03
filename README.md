{
  _id,
  userId,
  username,
  text,
  image,
  likes: [
    { userId, username }
  ],
  comments: [
    { userId, username, comment }
  ],
  createdAt
}
