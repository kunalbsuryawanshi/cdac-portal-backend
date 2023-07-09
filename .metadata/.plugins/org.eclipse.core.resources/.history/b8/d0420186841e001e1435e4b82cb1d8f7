package org.program.repository;

import org.program.entity.StudentLogin;
import org.springframework.data.jpa.repository.JpaRepository;

public interface StudentLoginRepository extends JpaRepository<StudentLogin, Integer> {
	
	public StudentLogin findByEmailAndPassword(String email, String password);
}
