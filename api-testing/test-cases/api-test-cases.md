# Test Case API - Reqres

## TC-API-001
**Endpoint:** GET /api/users/2  
**Skenario:** Mendapatkan data single user yang valid  

**Expected Result:**
- Status code 200
- Response berisi id, email, first_name, last_name, avatar

---

## TC-API-002
**Endpoint:** GET /api/users/23  
**Skenario:** User tidak ditemukan  

**Expected Result:**
- Status code 404
- Response kosong

---

## TC-API-003
**Endpoint:** GET /api/unknown
**Skenario:** mendapatkan list user  

**Expected Result:**
- Status code 200
- Response berisi page, per_page, total, total_pages,  data [id, name, year, color, pantone_value]

---

## TC-API-004
**Endpoint:** GET /api/unknown/2
**Skenario:** mendapatkan single list user  

**Expected Result:**
- Status code 200
- Response berisi data [id, name, year, color, pantone_value]

---

## TC-API-005
**Endpoint:** GET /api/unknown/23
**Skenario:** mendapatkan single list user not found

**Expected Result:**
- Status code 404
- Response berisi kosong

---

## TC-API-006
**Endpoint:** POST /api/login  
**Skenario:** Register gagal tanpa password  

**Expected Result:**
- Status code 400
- Response berisi error "Missing password"

---

## TC-API-007
**Endpoint:** POST /api/login  
**Skenario:** Login gagal tanpa password  

**Expected Result:**
- Status code 400
- Response berisi error "Missing password"

---

## TC-API-008
**Endpoint:** PUT /api/users/2
**Skenario:** Update Data user  

**Expected Result:**
- Status code 200
- Response berisi name, job, updatedAt, _meta

---

## TC-API-009
**Endpoint:** DELETE /api/users/2
**Skenario:** Delete user  

**Expected Result:**
- Status code 204
- Response berisi kosong
