# CHANGELOG

## 0.3.0

- [Breaking] Requires `lucia-auth` 0.3.0

## 0.2.0

- [Breaking] Requires `lucia-auth` 0.2.0

## 0.1.2

- Update peer dependency

## 0.1.1

- [Breaking] Removed `AuthRequest().clearSession()`
- [Breaking] `signOut()` will throw an error on failed session invalidation
- `AuthRequest().setSession()` can be called using `null` to delete all session cookies
- Update `lucia-auth` to 0.1.4